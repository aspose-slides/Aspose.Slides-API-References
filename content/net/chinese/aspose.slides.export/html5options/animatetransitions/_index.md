---
title: AnimateTransitions
second_title: Aspose.Sildes for .NET API Reference
description: 返回或设置过渡动画选项。可读/写布尔值。
type: docs
weight: 30
url: /zh/aspose.slides.export/html5options/animatetransitions/
---

## Html5Options.AnimateTransitions property

返回或设置过渡动画选项。可读/写布尔值。

```csharp
public bool AnimateTransitions { get; set; }
```

### 示例

示例：

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
  pres.Save("demo-animate-transitions.html", SaveFormat.Html5, new Html5Options()
  {
      AnimateTransitions = true
  });
}
```

### 另请参阅

* class [Html5Options](../../html5options)
* namespace [Aspose.Slides.Export](../../html5options)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->