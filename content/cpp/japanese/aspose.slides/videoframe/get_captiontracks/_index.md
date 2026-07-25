---
title: get_CaptionTracks()
second_title: Aspose.Slides の C++ API リファレンス
description: ビデオフレームに関連付けられたクローズドキャプションのコレクションを取得します。このプロパティは読み取り専用で、すべてのキャプショントラックを含む ICaptionsCollection を返します。
type: docs
weight: 261
url: /ja/aspose.slides/videoframe/get_captiontracks/
---
## VideoFrame::get_CaptionTracks() メソッド


このビデオフレームに関連付けられたクローズドキャプションのコレクションを取得します。このプロパティは読み取り専用で、すべてのキャプショントラックを含む [ICaptionsCollection](../../icaptionscollection/) を返します。

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::VideoFrame::get_CaptionTracks() override
```

## 備考


例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"video with captions.pptx");

for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    System::SharedPtr<IVideoFrame> videoFrame = System::AsCast<IVideoFrame>(shape);
    if (videoFrame != nullptr)
    {
        continue;
    }

    for (auto&& captionTrack : videoFrame->get_CaptionTracks())
    {
        // キャプションのバイナリデータを抽出し、ファイルに保存します
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ICaptionsCollection](../../icaptionscollection/)
* クラス [VideoFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)