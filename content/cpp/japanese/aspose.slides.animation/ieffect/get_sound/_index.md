---
title: get_Sound()
second_title: Aspose.Slides for C++ API リファレンス
description: エフェクトの埋め込みサウンドが定義されています。IAudio を参照してください。
type: docs
weight: 170
url: /ja/aspose.slides.animation/ieffect/get_sound/
---
## IEffect::get_Sound() メソッド


エフェクトの埋め込みサウンドが定義されています。[IAudio](../../../aspose.slides/iaudio/) を参照してください。

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::Animation::IEffect::get_Sound()=0
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IAudio](../../../aspose.slides/iaudio/)
* クラス [IEffect](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)