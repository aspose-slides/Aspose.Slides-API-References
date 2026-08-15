---
title: get_Videos()
second_title: Aspose.Slides for C++ API 參考文件
description: 返回簡報中所有嵌入式影片檔案的集合。只讀 IVideoCollection.
type: docs
weight: 235
url: /zh-hant/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() 方法

返回簡報中所有嵌入式影片檔案的集合。只讀 [IVideoCollection](../../ivideocollection/)。

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## 備註

以下範例說明如何在 PowerPoint [Presentation](../) 中建立嵌入式 [Video](../../video/) 框架。 
```cpp
// 實例化表示 PPTX 的 Presentation 類別
auto pres = System::MakeObject<Presentation>();

// 取得第一張投影片
auto slide = pres->get_Slides()->idx_get(0);

// 在簡報中嵌入影片
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// 新增影片框架
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// 將影片設定到影片框架
vf->set_EmbeddedVideo(video);
// 設定影片的播放模式與音量

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// 將 PPTX 檔寫入磁碟
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
以下範例說明如何將影片檔案的路徑直接傳遞給 AddVideoFrame 方法，以在 PowerPoint [Presentation](../) 中加入影片。 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
以下範例說明如何透過 BLOB 向 [Presentation](../) 新增大型檔案。 
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// 建立一個新的簡報，以加入影片
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// 讓我們將影片加入簡報 ─ 我們選擇 KeepLocked 行為，因為我們
// 不打算存取 "veryLargeVideo.avi" 檔案。
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// 儲存簡報。當輸出大型簡報時，記憶體使用量
// 在 pres 物件的生命週期中仍保持低水平。
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
以下範例說明如何從 PowerPoint [Presentation](../) 透過 BLOB 匯出大型檔案。 
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// 建立 Presentation 實例，並鎖定 "hugePresentationWithAudiosAndVideos.pptx" 檔案。
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// 讓我們將每個影片保存為檔案。為避免高記憶體使用量，我們需要一個緩衝區用來
// 從簡報的影片串流傳輸資料到新建立的影片檔案的串流。
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// 迭代所有影片
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // 開啟簡報的影片串流。請注意，我們特意避免存取屬性
    // 如 video.BinaryData —— 因為此屬性會回傳包含整個影片的位元組陣列，
    // 使位元組載入記憶體。我們使用 video.GetStream，會回傳 Stream，而不會
    //  需要我們將整個影片載入記憶體。
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // 記憶體使用量將保持低位元，無論影片或簡報的大小為何，
}
 // 如有需要，您可以對音訊檔案套用相同的步驟。
```
以下範例說明如何在 PowerPoint [Presentation](../) 中為影片加入超連結。 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
以下範例說明如何在 PowerPoint [Presentation](../) 中從 Web Source 建立帶有 [Video](../../video/) 的 [Video](../../video/) 框架。 
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // 新增 videoFrame
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // 載入 縮圖
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
以下範例說明如何從 PowerPoint [Presentation](../) 的投影片中提取 [Video](../../video/)。 
```cpp
// 實例化一個代表簡報檔案的 Presentation 物件
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

## 另請參考

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IVideoCollection](../../ivideocollection/)
* 類別 [Presentation](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)