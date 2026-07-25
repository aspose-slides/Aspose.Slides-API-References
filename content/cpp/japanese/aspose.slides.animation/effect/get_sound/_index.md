---
title: get_Sound()
second_title: C++ 用 Aspose.Slides API リファレンス
description: エフェクトの埋め込みサウンドを定義します。IAudio を参照してください。
type: docs
weight: 170
url: /ja/aspose.slides.animation/effect/get_sound/
---
## Effect::get_Sound() メソッド


エフェクトの埋め込みサウンドを定義します。参照 [IAudio](../../../aspose.slides/iaudio/)。

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Animation::Effect::get_Sound() override
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
* クラス [Effect](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)