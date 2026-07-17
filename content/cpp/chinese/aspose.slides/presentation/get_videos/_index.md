---
title: get_Videos()
second_title: Aspose.Slides for C++ API 参考
description: 返回演示文稿中所有嵌入式视频文件的集合。只读 IVideoCollection.
type: docs
weight: 235
url: /zh/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() 方法

返回演示文稿中所有嵌入式视频文件的集合。只读 [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## 备注

以下示例展示了如何在 PowerPoint [Presentation](../) 中创建嵌入式 [Video](../../video/) 帧。
```cpp
// 实例化表示 PPTX 的 Presentation 类
auto pres = System::MakeObject<Presentation>();

// 获取第一张幻灯片
auto slide = pres->get_Slides()->idx_get(0);

// 在演示文稿中嵌入视频
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// 添加视频帧
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// 将视频设置到视频帧
vf->set_EmbeddedVideo(video);
// 设置视频的播放模式和音量

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// 将 PPTX 文件写入磁盘
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
以下示例展示了如何将视频文件路径直接传递给 AddVideoFrame 方法，以在 PowerPoint [Presentation](../) 中添加视频。
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
以下示例展示了如何通过 BLOB 将大文件添加到 [Presentation](../)。
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// 创建一个将要添加视频的新演示文稿
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// 让我们将视频添加到演示文稿中 - 我们选择 KeepLocked 行为因为我们
// 不打算访问 "veryLargeVideo.avi" 文件。
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// 保存演示文稿。当输出大型演示文稿时，内存消耗
// 在 pres 对象的整个生命周期中保持低水平
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
以下示例展示了如何从 PowerPoint [Presentation](../) 通过 BLOB 导出大文件。
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// 创建 Presentation 实例，并锁定 "hugePresentationWithAudiosAndVideos.pptx" 文件。
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// 让我们将每个视频保存到文件。为防止内存占用过高，我们需要一个缓冲区来使用
// 将演示文稿的视频流数据传输到新创建的视频文件的流。
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// 遍历视频
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // 打开演示文稿视频流。请注意，我们有意避免访问属性
    // 如 video.BinaryData —— 因为此属性返回包含完整视频的字节数组，进而
    // 导致字节加载到内存中。我们使用 video.GetStream，它将返回 Stream —— 并且不会
    // 需要我们将整个视频加载到内存中。
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // 无论视频或演示文稿大小如何，内存消耗都将保持低水平，
}
// 如有需要，您可以对音频文件执行相同的步骤。
```
以下示例展示了如何在 PowerPoint [Presentation](../) 中为视频添加超链接。
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
以下示例展示了如何在 PowerPoint [Presentation](../) 中使用来自 Web 源的 [Video](../../video/) 创建 [Video](../../video/) 帧。
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // 添加视频帧
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // 加载缩略图
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
以下示例展示了如何从 PowerPoint [Presentation](../) 幻灯片中提取 [Video](../../video/)。
```cpp
// 实例化一个表示演示文稿文件的 Presentation 对象
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

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IVideoCollection](../../ivideocollection/)
* 类 [Presentation](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)