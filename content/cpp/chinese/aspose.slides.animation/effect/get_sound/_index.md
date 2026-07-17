---
title: get_Sound()
second_title: Aspose.Slides for C++ API 参考
description: 为效果定义了嵌入式声音。阅读 IAudio.
type: docs
weight: 170
url: /zh/aspose.slides.animation/effect/get_sound/
---
## Effect::get_Sound() 方法

定义了效果的嵌入式声音。阅读 [IAudio](../../../aspose.slides/iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Animation::Effect::get_Sound() override
```

## 备注



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// 获取幻灯片的效果序列
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // 以字节数组形式提取效果声音
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IAudio](../../../aspose.slides/iaudio/)
* 类 [Effect](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)