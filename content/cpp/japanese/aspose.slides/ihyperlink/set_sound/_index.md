---
title: set_Sound()
second_title: Aspose.Slides for C++ API リファレンス
description: ハイパーリンクの再生音を表します。IAudioを書き込みます。
type: docs
weight: 196
url: /ja/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) メソッド


ハイパーリンクの再生音を表します。[IAudio](../../iaudio/)を書き込みます。

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IAudio](../../iaudio/)
* クラス [IHyperlink](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)