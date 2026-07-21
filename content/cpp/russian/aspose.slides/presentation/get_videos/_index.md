---
title: get_Videos()
second_title: Aspose.Slides для C++ API Справка
description: Возвращает коллекцию всех встроенных видеофайлов в презентацию. Только для чтения IVideoCollection.
type: docs
weight: 235
url: /ru/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() метод


Возвращает коллекцию всех встроенных видеофайлов в презентацию. Только для чтения [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## Примечания


Следующие примеры показывают, как создать встроенный [Video](../../video/) Frame в PowerPoint [Presentation](../). 
```cpp
// Создать объект класса Presentation, представляющего PPTX
auto pres = System::MakeObject<Presentation>();

// Получить первый слайд
auto slide = pres->get_Slides()->idx_get(0);

// Встроить видео в презентацию
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// Добавить видеорамку
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// Установить видео в видеорамку
vf->set_EmbeddedVideo(video);
// Установить режим воспроизведения и громкость видео

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// Сохранить PPTX файл на диск
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
 Следующие примеры показывают, как добавить видео, передавая путь к видеофайлу напрямую в метод AddVideoFrame для PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
 Следующие примеры показывают, как добавить большой файл через BLOB в [Presentation](../). 
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// Создаёт новую презентацию, в которую будет добавлено видео
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// Добавим видео в презентацию — мы выбрали поведение KeepLocked, потому что мы
// не планируем обращаться к файлу "veryLargeVideo.avi" file.
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// Сохраняет презентацию. Пока выводится большая презентация,
// потребление памяти остаётся низким на протяжении жизненного цикла объекта pres
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
 Следующие примеры показывают, как экспортировать большой файл через BLOB из PowerPoint [Presentation](../). 
```cpp
// Создает экземпляр Presentation, блокирует файл "hugePresentationWithAudiosAndVideos.pptx".
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// Сохраним каждое видео в отдельный файл. Чтобы предотвратить высокое потребление памяти, нам нужен буфер, который будет использоваться
// для передачи данных из видеопотока презентации в поток нового создаваемого видеофайла.
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// Iterates through the videos
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // Открывает видеопоток презентации. Обратите внимание, что мы сознательно избегаем доступа к свойствам
    // таким как video.BinaryData — потому что это свойство возвращает массив байт, содержащий полное видео, что затем
    // приводит к загрузке байтов в память. Мы используем video.GetStream, который возвращает Stream и НЕ
    //  требует загружать всё видео в память.
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // Потребление памяти останется низким независимо от размера видео или презентации,
}
// При необходимости вы можете выполнить те же шаги для аудиофайлов.
```
 Следующие примеры показывают, как добавить гиперссылку на видео в PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
 Следующие примеры показывают, как создать [Video](../../video/) Frame с [Video](../../video/) из веб-источника в PowerPoint [Presentation](../). 
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // Добавить видеорамку
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // Загрузить миниатюру
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
 Следующие примеры показывают, как извлечь [Video](../../video/) из слайда PowerPoint [Presentation](../). 
```cpp
// Создать объект Presentation, представляющий файл презентации
auto presentation = System::MakeObject<Presentation>(u"Video.pptx");

for (auto&& slide : presentation->get_Slides())
{
    for (auto&& shape : slide->get_Shapes())
    {
        if (System::ObjectExt::Is<VideoFrame>(shape))
        {
            System::SharedPtr<IVideoFrame> vf = System::AsCast<IVideoFrame>(shape);
            System::String type = vf->get_EmbeddedVideo()->get_ContentType();
            int32_t ss = type.LastIndexOf(u'/');
            type = type.Remove(0, type.LastIndexOf(u'/') + 1);
            System::ArrayPtr<uint8_t> buffer = vf->get_EmbeddedVideo()->get_BinaryData();
            auto stream = System::MakeObject<System::IO::FileStream>(System::String(u"NewVideo_out.") + type,
                                                                     System::IO::FileMode::Create,
                                                                     System::IO::FileAccess::Write,
                                                                     System::IO::FileShare::Read);
            stream->Write(buffer, 0, buffer->get_Length());
        }
    }
}
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IVideoCollection](../../ivideocollection/)
* Класс [Presentation](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)