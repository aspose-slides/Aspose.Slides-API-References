---
title: get_AfterAnimationType()
second_title: Aspose.Slides C++ API 参考
description: 为效果定义了后动画类型。请阅读 AfterAnimationType。
type: docs
weight: 222
url: /zh/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() 方法


为效果定义了后动画类型。请阅读[AfterAnimationType](../../afteranimationtype/)。

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## 备注



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 获取第一张幻灯片的第一个效果。
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// 将效果的后动画更改为“在下一次鼠标点击时隐藏”
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## 另见

* 枚举 [AfterAnimationType](../../afteranimationtype/)
* 类 [IEffect](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)