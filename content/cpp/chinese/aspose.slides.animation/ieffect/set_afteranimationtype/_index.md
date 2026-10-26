---
title: set_AfterAnimationType()
second_title: Aspose.Slides for C++ API 参考
description: 为效果定义后动画类型。写入 AfterAnimationType。
type: docs
weight: 235
url: /zh/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) 方法


为效果定义后动画类型。写入 [AfterAnimationType](../../afteranimationtype/)。

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## 备注



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 获取第一张幻灯片的第一个效果。
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// 将效果的后动画更改为 "在下次鼠标点击时隐藏"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## 参见

* 枚举 [AfterAnimationType](../../afteranimationtype/)
* 类 [IEffect](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)