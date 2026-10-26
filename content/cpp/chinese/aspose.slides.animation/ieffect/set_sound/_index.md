---
title: set_Sound()
second_title: Aspose.Slides C++ API 参考
description: 为效果定义嵌入式声音。写入 IAudio.
type: docs
weight: 183
url: /zh/aspose.slides.animation/ieffect/set_sound/
---
## IEffect::set_Sound(System::SharedPtr\<IAudio\>) 方法


为效果定义嵌入式声音。写入 [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_Sound(System::SharedPtr<IAudio> value)=0
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

    // 提取效果声音为字节数组
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IAudio](../../../aspose.slides/iaudio/)
* 类 [IEffect](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)