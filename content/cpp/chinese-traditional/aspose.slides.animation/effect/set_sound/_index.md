---
title: set_Sound()
second_title: Aspose.Slides for C++ API 參考
description: 為效果定義內嵌聲音。寫入 IAudio.
type: docs
weight: 183
url: /zh-hant/aspose.slides.animation/effect/set_sound/
---
## Effect::set_Sound(System::SharedPtr\<IAudio\>) 方法

為效果定義內嵌聲音。寫入 [IAudio](../../../aspose.slides/iaudio/).

```cpp
void Aspose::Slides::Animation::Effect::set_Sound(System::SharedPtr<IAudio> value) override
```

## 備註

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// 取得投影片的效果序列
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // 以位元組陣列提取效果聲音
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAudio](../../../aspose.slides/iaudio/)
* 類別 [Effect](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)