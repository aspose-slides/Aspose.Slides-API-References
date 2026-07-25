---
title: get_Videos()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーション内のすべての埋め込みビデオファイルのコレクションを返します。読み取り専用 IVideoCollection.
type: docs
weight: 235
url: /ja/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() メソッド

プレゼンテーション内のすべての埋め込みビデオ ファイルのコレクションを返します。読み取り専用 [IVideoCollection](../../ivideocollection/)。

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## 備考

次の例は、PowerPoint [Presentation](../) で埋め込み [Video](../../video/) フレームを作成する方法を示しています。
```cpp
// PPTX を表す Presentation クラスのインスタンスを作成
auto pres = System::MakeObject<Presentation>();

// 最初のスライドを取得
auto slide = pres->get_Slides()->idx_get(0);

// プレゼンテーションにビデオを埋め込む
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// ビデオ フレームを追加
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// ビデオ フレームにビデオを設定
vf->set_EmbeddedVideo(video);
// ビデオの再生モードと音量を設定

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// PPTX ファイルをディスクに保存
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
 次の例は、PowerPoint [Presentation](../) 用の AddVideoFrame メソッドにビデオ ファイルへのパスを直接渡してビデオを追加する方法を示しています。
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
 次の例は、BLOB を介して大きなファイルを [Presentation](../) に追加する方法を示しています。
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// ビデオが追加される新しいプレゼンテーションを作成します
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// ビデオをプレゼンテーションに追加しましょう - KeepLocked 動作を選択したのは、
// 「veryLargeVideo.avi」ファイルにアクセスするつもりがないためです。
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// プレゼンテーションを保存します。大きなプレゼンテーションが出力される間、
// pres オブジェクトのライフサイクル全体でメモリ使用量は低く抑えられます
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
 次の例は、PowerPoint [Presentation](../) から BLOB を介して大きなファイルをエクスポートする方法を示しています。
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// Presentation のインスタンスを作成し、"hugePresentationWithAudiosAndVideos.pptx" ファイルをロックします。
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// 各ビデオをファイルに保存します。メモリ使用量の増加を防ぐため、バッファが必要です。
// プレゼンテーションのビデオストリームから新規作成したビデオファイル用のストリームへデータを転送するために使用します。
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// ビデオを列挙します
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // プレゼンテーションのビデオストリームを開きます。意図的にプロパティへのアクセスを避けたことに注意してください。
    // video.BinaryData のようなプロパティは、完全なビデオを含むバイト配列を返すため、
    // メモリにバイトをロードしてしまいます。代わりに video.GetStream を使用し、Stream を取得します - そして
    //  メモリ全体にビデオ全体をロードする必要はありません。
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // ビデオやプレゼンテーションのサイズに関係なく、メモリ消費は低く抑えられます。
}
// 必要に応じて、オーディオファイルにも同じ手順を適用できます。
```
 次の例は、PowerPoint [Presentation](../) のビデオにハイパーリンクを追加する方法を示しています。
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
 次の例は、PowerPoint [Presentation](../) の Web ソースから [Video](../../video/) を使用して [Video](../../video/) フレームを作成する方法を示しています。
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // ビデオフレームを追加
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // サムネイルを読み込む
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
 次の例は、PowerPoint [Presentation](../) のスライドから [Video](../../video/) を抽出する方法を示しています。
```cpp
// プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化
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

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IVideoCollection](../../ivideocollection/)
* クラス [Presentation](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)