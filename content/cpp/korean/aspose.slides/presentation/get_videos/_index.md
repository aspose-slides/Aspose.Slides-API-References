---
title: get_Videos()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션에 포함된 모든 임베드된 비디오 파일의 컬렉션을 반환합니다. 읽기 전용 IVideoCollection.
type: docs
weight: 235
url: /ko/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() 메서드

프레젠테이션에 포함된 모든 임베드된 비디오 파일의 컬렉션을 반환합니다. 읽기 전용 [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## 비고

다음 예제는 PowerPoint [Presentation](../)에서 임베드된 [Video](../../video/) 프레임을 생성하는 방법을 보여줍니다.
```cpp
// PPTX를 나타내는 Presentation 클래스를 인스턴스화합니다
auto pres = System::MakeObject<Presentation>();

// 첫 번째 슬라이드를 가져옵니다
auto slide = pres->get_Slides()->idx_get(0);

// 프레젠테이션에 비디오를 삽입합니다
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// 비디오 프레임을 추가합니다
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// 비디오를 비디오 프레임에 설정합니다
vf->set_EmbeddedVideo(video);
// 비디오의 재생 모드와 볼륨을 설정합니다

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// PPTX 파일을 디스크에 저장합니다
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
다음 예제는 PowerPoint [Presentation](../)에서 AddVideoFrame 메서드에 비디오 파일 경로를 직접 전달하여 비디오를 추가하는 방법을 보여줍니다.
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
다음 예제는 BLOB를 통해 [Presentation](../)에 대용량 파일을 추가하는 방법을 보여줍니다.
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// 비디오가 추가될 새 프레젠테이션을 생성합니다
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// 프레젠테이션에 비디오를 추가합니다 - KeepLocked 동작을 선택한 이유는
// "veryLargeVideo.avi" 파일에 접근할 의도가 없기 때문입니다.
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// 프레젠테이션을 저장합니다. 대용량 프레젠테이션이 출력되는 동안
// 메모리 사용량은 pres 객체의 수명 동안 낮게 유지됩니다.
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
다음 예제는 PowerPoint [Presentation](../)에서 BLOB를 통해 대용량 파일을 내보내는 방법을 보여줍니다.
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// Presentation 인스턴스를 생성하고, "hugePresentationWithAudiosAndVideos.pptx" 파일을 잠급니다.
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// 각 비디오를 파일에 저장합니다. 높은 메모리 사용을 방지하기 위해 사용할 버퍼가 필요합니다.
// 프레젠테이션의 비디오 스트림에서 새로 만든 비디오 파일용 스트림으로 데이터를 전송하기 위해서입니다.
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// 비디오들을 순회합니다
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // 프레젠테이션 비디오 스트림을 엽니다. 주의할 점은 우리는 의도적으로 속성에 접근하는 것을 피했다는 것입니다
    // 예를 들어 video.BinaryData - 이 속성은 전체 비디오를 포함하는 바이트 배열을 반환하기 때문에
    // 메모리로 바이트를 로드하게 됩니다. 우리는 video.GetStream을 사용하며, 이는 Stream을 반환하고 - 메모리에 전체 비디오를 로드하도록 요구하지 않습니다
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // 비디오나 프레젠테이션의 크기에 관계없이 메모리 사용량이 낮게 유지됩니다,
}
 // 필요하면 오디오 파일에 대해 동일한 절차를 적용할 수 있습니다.
```
다음 예제는 PowerPoint [Presentation](../)에서 비디오에 하이퍼링크를 추가하는 방법을 보여줍니다.
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
다음 예제는 PowerPoint [Presentation](../)에서 웹 소스의 [Video](../../video/)를 사용하여 [Video](../../video/) 프레임을 생성하는 방법을 보여줍니다.
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // 비디오 프레임을 추가합니다
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // 썸네일 로드
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
다음 예제는 PowerPoint [Presentation](../) 슬라이드에서 [Video](../../video/)를 추출하는 방법을 보여줍니다.
```cpp
// 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
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

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideoCollection](../../ivideocollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)