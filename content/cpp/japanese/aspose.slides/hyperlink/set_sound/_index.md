---
title: set_Sound()
second_title: Aspose.Slides for C++ API リファレンス
description: ハイパーリンクの再生サウンドを表します。IAudioを書き込みます。
type: docs
weight: 300
url: /ja/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) メソッド


ハイパーリンクの再生サウンドを表します。[IAudio](../../iaudio/)を書き込みます。

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## 備考



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 最初のシェイプのハイパーリンクを取得
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // ハイパーリンクのサウンドをバイト配列で抽出
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAudio](../../iaudio/)
* クラス [Hyperlink](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)