---
title: GetEffective()
second_title: Aspose.Slides for C++ API 参考
description: 获取应用继承后的有效文本框格式数据。
type: docs
weight: 391
url: /zh/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() 方法

获取应用继承后的有效文本框格式数据。

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```

### 返回值

一个 [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).
## 备注

此示例演示获取一些有效的文本框格式属性。 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextFrameFormat = shape->get_TextFrame()->get_TextFrameFormat()->GetEffective();

Console::WriteLine(String(u"Anchoring type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AnchoringType()));
Console::WriteLine(String(u"Autofit type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AutofitType()));
Console::WriteLine(String(u"Text vertical type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_TextVerticalType()));
Console::WriteLine(u"Margins");
Console::WriteLine(String(u"   Left: ") + effectiveTextFrameFormat->get_MarginLeft());
Console::WriteLine(String(u"   Top: ") + effectiveTextFrameFormat->get_MarginTop());
Console::WriteLine(String(u"   Right: ") + effectiveTextFrameFormat->get_MarginRight());
Console::WriteLine(String(u"   Bottom: ") + effectiveTextFrameFormat->get_MarginBottom());
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* 类 [TextFrameFormat](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)