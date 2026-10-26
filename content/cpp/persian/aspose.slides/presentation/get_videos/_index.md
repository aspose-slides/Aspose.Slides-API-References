---
title: get_Videos()
second_title: مرجع API Aspose.Slides برای C++
description: مجموعه تمام فایل‌های ویدئویی جاسازی‌شده در ارائه را برمی‌گرداند. فقط-خواندنی IVideoCollection.
type: docs
weight: 235
url: /fa/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() متد


مجموعهٔ تمام فایل‌های ویدئوی جاسازی‌شده در ارائه را برمی‌گرداند. فقط-خواندنی [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## نکات


مثال‌های زیر نشان می‌دهند که چگونه یک [Video](../../video/) Frame جاسازی‌شده در یک PowerPoint [Presentation](../) ایجاد کنید. 
```cpp
// نمونه‌سازی کلاس Presentation که نمایانگر فایل PPTX است
auto pres = System::MakeObject<Presentation>();

// دریافت اولین اسلاید
auto slide = pres->get_Slides()->idx_get(0);

// جاسازی ویدئو درون ارائه
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// افزودن فریم ویدئو
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// تنظیم ویدئو برای فریم ویدئویی
vf->set_EmbeddedVideo(video);
// تنظیم حالت پخش و حجم صدا برای ویدئو

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// نوشتن فایل PPTX به دیسک
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
 مثال‌های زیر نشان می‌دهند که چگونه یک ویدئو را با عبور مسیر به فایل ویدئویی مستقیماً به متد AddVideoFrame برای PowerPoint [Presentation](../) اضافه کنید. 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
 مثال‌های زیر نشان می‌دهند که چگونه یک فایل بزرگ را از طریق BLOB به یک [Presentation](../) اضافه کنید. 
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// یک ارائه جدید ایجاد می‌کند که ویدئو به آن اضافه خواهد شد
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// بیایید ویدئو را به ارائه اضافه کنیم - رفتار KeepLocked را انتخاب کردیم چون ما
// قصد دسترسی به فایل "veryLargeVideo.avi" را نداریم.
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// ارائه را ذخیره می‌کند. در حالی که یک ارائه بزرگ خروجی می‌شود، مصرف حافظه
// در طول دورهٔ حیات شیء pres کم می‌ماند
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
 مثال‌های زیر نشان می‌دهند که چگونه یک فایل بزرگ را از طریق BLOB از PowerPoint [Presentation](../) صادر کنید. 
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// یک نمونه از Presentation ایجاد می‌کند و فایل "hugePresentationWithAudiosAndVideos.pptx" را قفل می‌گیرد.
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// بیایید هر ویدئو را در یک فایل ذخیره کنیم. برای جلوگیری از استفاده زیاد حافظه، به یک بافر نیاز داریم که استفاده شود
// برای انتقال داده‌ها از جریان ویدئوی ارائه به یک جریان برای فایل ویدئوی تازه ایجاد شده.
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// بر روی ویدئوها تکرار می‌کند
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // جریان ویدئوی ارائه را باز می‌کند. لطفاً توجه داشته باشید که ما عمداً از دسترسی به ویژگی‌ها اجتناب کردیم
    // مانند video.BinaryData - چون این ویژگی یک آرایه بایتی شامل تمام ویدئو برمی‌گرداند که سپس
    // باعث بارگذاری بایت‌ها در حافظه می‌شود. ما از video.GetStream استفاده می‌کنیم که یک Stream برمی‌گرداند - و does NOT
    //  نیاز به بارگذاری کل ویدئو در حافظه ندارد.
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // مصرف حافظه حتی با هر اندازه‌ای از ویدئو یا ارائه کم می‌ماند،
}
// در صورت نیاز می‌توانید همین مراحل را برای فایل‌های صوتی اعمال کنید.
```
 مثال‌های زیر نشان می‌دهند که چگونه یک پیوند-هایپر را به یک ویدئو در یک PowerPoint [Presentation](../) اضافه کنید. 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
 مثال‌های زیر نشان می‌دهند که چگونه یک [Video](../../video/) Frame با [Video](../../video/) از منبع وب در یک PowerPoint [Presentation](../) ایجاد کنید. 
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // افزودن فریم ویدئو
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // بارگذاری تصویر بندانگشتی
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
 مثال‌های زیر نشان می‌دهند که چگونه [Video](../../video/) را از اسلاید PowerPoint [Presentation](../) استخراج کنید. 
```cpp
// یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
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

## مراجع مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IVideoCollection](../../ivideocollection/)
* کلاس [Presentation](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)