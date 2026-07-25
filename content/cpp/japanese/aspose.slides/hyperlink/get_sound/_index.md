---
title: get_Sound()
second_title: Aspose.Slides for C++ API リファレンス
description: ハイパーリンクの再生サウンドを表します。IAudio を参照してください。
type: docs
weight: 287
url: /ja/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() メソッド


ハイパーリンクの再生サウンドを表します。[IAudio](../../iaudio/) を参照してください。

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```

## 備考



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 最初のシェイプのハイパーリンクを取得
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // ハイパーリンクのサウンドをバイト配列として抽出
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAudio](../../iaudio/)
* クラス [Hyperlink](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)