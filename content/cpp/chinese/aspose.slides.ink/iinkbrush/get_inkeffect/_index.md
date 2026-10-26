---
title: get_InkEffect()
second_title: Aspose.Slides C++ API 参考
description: "获取定义墨迹笔画视觉样式的墨效类型（例如，Galaxy，Gold，Silver）。该值从画笔属性 \"inkEffects\" 解析。如果未指定已识别的效果，InkEffectType::NotDefined 将被返回。"
type: docs
weight: 53
url: /zh/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() 方法

获取定义墨迹视觉样式的墨效类型（例如，Galaxy，Gold，Silver）。该值来自画笔属性 "inkEffects"。如果未指定已识别的效果，[InkEffectType::NotDefined](../../inkeffecttype/) 将被返回。

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## 备注

示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## 另请参见

* 枚举 [InkEffectType](../../inkeffecttype/)
* 类 [IInkBrush](../)
* 命名空间 [Aspose::Slides::Ink](../../)
* 库 [Aspose.Slides](../../../)