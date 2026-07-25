---
title: get_CaptionTracks()
second_title: Aspose.Slides for C++ API リファレンス
description: オーディオフレームに関連付けられたクローズドキャプションのコレクションを取得します。このプロパティは読み取り専用で、すべてのキャプショントラックを含む ICaptionsCollection を返します。
type: docs
weight: 456
url: /ja/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() メソッド

オーディオフレームに関連付けられたクローズドキャプションのコレクションを取得します。このプロパティは読み取り専用で、すべてのキャプショントラックを含む [ICaptionsCollection](../../icaptionscollection/) を返します。

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
```

## 備考

例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // キャプショントラックのバイナリデータを .vtt ファイルとして保存します
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ICaptionsCollection](../../icaptionscollection/)
* クラス [AudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)