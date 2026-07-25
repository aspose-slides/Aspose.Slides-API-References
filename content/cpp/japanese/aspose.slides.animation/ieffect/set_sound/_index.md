---
title: set_Sound()
second_title: Aspose.Slides for C++ API リファレンス
description: エフェクトの埋め込みサウンドを定義します。IAudio を記述します。
type: docs
weight: 183
url: /ja/aspose.slides.animation/ieffect/set_sound/
---
## IEffect::set_Sound(System::SharedPtr\<IAudio\>) メソッド


エフェクトの埋め込みサウンドを定義します。[IAudio](../../../aspose.slides/iaudio/) を記述します。

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_Sound(System::SharedPtr<IAudio> value)=0
```

## 備考



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// スライドのエフェクトシーケンスを取得します
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // エフェクトのサウンドをバイト配列として抽出します
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IAudio](../../../aspose.slides/iaudio/)
* クラス [IEffect](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)