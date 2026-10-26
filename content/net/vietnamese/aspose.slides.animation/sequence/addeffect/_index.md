---
title: AddEffect
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Thêm hiệu ứng mới vào cuối chuỗi.
type: docs
weight: 40
url: /vi/aspose.slides.animation/sequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Thêm hiệu ứng mới vào cuối chuỗi.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shape | IShape | Đối tượng Shape [`IShape`](../../../aspose.slides/ishape) để thêm một hiệu ứng |
| effectType | EffectType | Kiểu của một hiệu ứng hoạt hình [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Các phụ loại của hiệu ứng hoạt hình [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Kiểu kích hoạt của hiệu ứng [`EffectTriggerType`](../../effecttriggertype) |

### Return Value

Đối tượng hiệu ứng mới [`IEffect`](../../ieffect)

### See Also

* giao diện [IEffect](../../ieffect)
* giao diện [IShape](../../../aspose.slides/ishape)
* liệt kê [EffectType](../../effecttype)
* liệt kê [EffectSubtype](../../effectsubtype)
* liệt kê [EffectTriggerType](../../effecttriggertype)
* lớp [Sequence](../../sequence)
* không gian tên [Aspose.Slides.Animation](../../sequence)
* tập hợp [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Thêm hiệu ứng hoạt hình mới cho đoạn văn vào cuối chuỗi.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| paragraph | IParagraph | Đối tượng Paragraph [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Kiểu của một hiệu ứng hoạt hình [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Các phụ loại của hiệu ứng hoạt hình [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Kiểu kích hoạt của hiệu ứng [`EffectTriggerType`](../../effecttriggertype) |

### Return Value

Đối tượng hiệu ứng mới [`IEffect`](../../ieffect)

### Examples

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // chọn đoạn văn để thêm hiệu ứng
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // thêm hiệu ứng hoạt hình Fly vào đoạn văn đã chọn
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### See Also

* giao diện [IEffect](../../ieffect)
* giao diện [IParagraph](../../../aspose.slides/iparagraph)
* liệt kê [EffectType](../../effecttype)
* liệt kê [EffectSubtype](../../effectsubtype)
* liệt kê [EffectTriggerType](../../effecttriggertype)
* lớp [Sequence](../../sequence)
* không gian tên [Aspose.Slides.Animation](../../sequence)
* tập hợp [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Thêm hiệu ứng hoạt hình biểu đồ mới cho danh mục hoặc chuỗi vào cuối chuỗi.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chart | IChart | Đối tượng Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Kiểu của một hiệu ứng hoạt hình [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Chỉ mục Int32 |
| effectType | EffectType | Kiểu của một hiệu ứng hoạt hình [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Các phụ loại của hiệu ứng hoạt hình [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Kiểu kích hoạt của hiệu ứng [`EffectTriggerType`](../../effecttriggertype) |

### Return Value

Đối tượng hiệu ứng mới [`IEffect`](../../ieffect)

### See Also

* giao diện [IEffect](../../ieffect)
* giao diện [IChart](../../../aspose.slides.charts/ichart)
* liệt kê [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* liệt kê [EffectType](../../effecttype)
* liệt kê [EffectSubtype](../../effectsubtype)
* liệt kê [EffectTriggerType](../../effecttriggertype)
* lớp [Sequence](../../sequence)
* không gian tên [Aspose.Slides.Animation](../../sequence)
* tập hợp [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Thêm hiệu ứng hoạt hình biểu đồ mới cho các phần tử trong danh mục hoặc chuỗi vào cuối chuỗi.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chart | IChart | Đối tượng Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Kiểu của một hiệu ứng hoạt hình [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Chỉ mục của chuỗi biểu đồ Int32 |
| categoriesIndex | Int32 | Chỉ mục của danh mục Int32 |
| effectType | EffectType | Kiểu của một hiệu ứng hoạt hình [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Các phụ loại của hiệu ứng hoạt hình [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Kiểu kích hoạt của hiệu ứng [`EffectTriggerType`](../../effecttriggertype) |

### Return Value

Đối tượng hiệu ứng mới [`IEffect`](../../ieffect)

### See Also

* giao diện [IEffect](../../ieffect)
* giao diện [IChart](../../../aspose.slides.charts/ichart)
* liệt kê [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* liệt kê [EffectType](../../effecttype)
* liệt kê [EffectSubtype](../../effectsubtype)
* liệt kê [EffectTriggerType](../../effecttriggertype)
* lớp [Sequence](../../sequence)
* không gian tên [Aspose.Slides.Animation](../../sequence)
* tập hợp [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->