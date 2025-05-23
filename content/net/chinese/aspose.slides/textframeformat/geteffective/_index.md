---
title: GetEffective
second_title: Aspose.Slides for .NET API 参考
description: 获取应用了继承的有效文本框架格式数据
type: docs
weight: 170
url: /zh/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat.GetEffective method

获取应用了继承的有效文本框架格式数据。

```csharp
public ITextFrameFormatEffectiveData GetEffective()
```

### 返回值

A[`ITextFrameFormatEffectiveData`](../../itextframeformateffectivedata)。

### 例子

此示例演示了获取一些有效的文本框架格式属性。

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
    IAutoShape shape = pres.Slides[0].Shapes[0] as IAutoShape;
    ITextFrameFormatEffectiveData effectiveTextFrameFormat = shape.TextFrame.TextFrameFormat.GetEffective();
   
    Console.WriteLine("Anchoring type: " + effectiveTextFrameFormat.AnchoringType);
    Console.WriteLine("Autofit type: " + effectiveTextFrameFormat.AutofitType);
    Console.WriteLine("Text vertical type: " + effectiveTextFrameFormat.TextVerticalType);
    Console.WriteLine("Margins");
    Console.WriteLine("   Left: " + effectiveTextFrameFormat.MarginLeft);
    Console.WriteLine("   Top: " + effectiveTextFrameFormat.MarginTop);
    Console.WriteLine("   Right: " + effectiveTextFrameFormat.MarginRight);
    Console.WriteLine("   Bottom: " + effectiveTextFrameFormat.MarginBottom);
}
```

### 也可以看看

* interface [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata)
* class [TextFrameFormat](../../textframeformat)
* 命名空间 [Aspose.Slides](../../textframeformat)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
