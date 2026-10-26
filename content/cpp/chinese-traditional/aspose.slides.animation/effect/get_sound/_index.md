---
title: get_Sound()
second_title: Aspose.Slides for C++ API 參考文件
description: 為效果定義嵌入式聲音。請閱讀 IAudio.
type: docs
weight: 170
url: /zh-hant/aspose.slides.animation/effect/get_sound/
---
## Effect::get_Sound() 方法


已定義效果的嵌入式聲音。閱讀 [IAudio](../../../aspose.slides/iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Animation::Effect::get_Sound() override
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

    // 以位元組陣列提取效果音訊
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAudio](../../../aspose.slides/iaudio/)
* 類別 [Effect](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)