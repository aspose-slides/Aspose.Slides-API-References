---
title: Remove
second_title: Aspose.Sildes for .NET API Reference
description: 从演示文稿中删除布局。
type: docs
weight: 90
url: /zh/aspose.slides/layoutslide/remove/
---

## LayoutSlide.Remove 方法

从演示文稿中删除布局。

```csharp
public void Remove()
```

### 异常

| exception | condition |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | 如果布局已经从演示文稿中删除或布局在演示文稿中被使用（其 HasDependingSlides 属性为 true），则抛出该异常。 |

### 备注

为了避免抛出 PptxEditException，在之前检查布局的 HasDependingSlides 属性。

### 另见

* class [LayoutSlide](../../layoutslide)
* namespace [Aspose.Slides](../../layoutslide)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->