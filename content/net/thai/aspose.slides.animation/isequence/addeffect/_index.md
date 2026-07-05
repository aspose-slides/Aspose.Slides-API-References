---
title: AddEffect
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: เพิ่มเอฟเฟกต์ใหม่ไปยังส่วนท้ายของลำดับ.
type: docs
weight: 50
url: /th/aspose.slides.animation/isequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

เพิ่มเอฟเฟกต์ใหม่ไปยังส่วนท้ายของลำดับ

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| shape | IShape | ออบเจ็กต์ Shape [`IShape`](../../../aspose.slides/ishape) สำหรับเพิ่มเอฟเฟกต์ |
| effectType | EffectType | ชนิดของเอฟเฟกต์แอนิเมชัน [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | ชนิดย่อยของเอฟเฟกต์แอนิเมชัน [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | ประเภทการเรียกใช้ของเอฟเฟกต์ [`EffectTriggerType`](../../effecttriggertype) |

### ค่าที่คืนค่า

ออบเจ็กต์เอฟเฟกต์ใหม่ [`IEffect`](../../ieffect)

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IEffect](../../ieffect)
* อินเทอร์เฟซ [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* อินเทอร์เฟซ [ISequence](../../isequence)
* เนมสเปซ [Aspose.Slides.Animation](../../isequence)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

เพิ่มเอฟเฟกต์แอนิเมชันใหม่สำหรับย่อหน้าไปยังส่วนท้ายของลำดับ

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| paragraph | IParagraph | ออบเจ็กต์ Paragraph [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | ชนิดของเอฟเฟกต์แอนิเมชัน [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | ชนิดย่อยของเอฟเฟกต์แอนิเมชัน [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | ประเภทการเรียกใช้ของเอฟเฟกต์ [`EffectTriggerType`](../../effecttriggertype) |

### ค่าที่คืนค่า

ออบเจ็กต์เอฟเฟกต์ใหม่ [`IEffect`](../../ieffect)

### ตัวอย่าง

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // เลือกย่อหน้าเพื่อเพิ่มเอฟเฟกต์
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // เพิ่มเอฟเฟกต์แอนิเมชัน Fly ให้กับย่อหน้าที่เลือก
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IEffect](../../ieffect)
* อินเทอร์เฟซ [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* อินเทอร์เฟซ [ISequence](../../isequence)
* เนมสเปซ [Aspose.Slides.Animation](../../isequence)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

เพิ่มเอฟเฟกต์แอนิเมชันใหม่สำหรับแผนภูมิประเภทหรือชุดข้อมูลไปยังส่วนท้ายของลำดับ

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| chart | IChart | ออบเจ็กต์ Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | ชนิดของเอฟเฟกต์แอนิเมชัน [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | ดัชนี Int32 |
| effectType | EffectType | ชนิดของเอฟเฟกต์แอนิเมชัน [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | ชนิดย่อยของเอฟเฟกต์แอนิเมชัน [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | ประเภทการเรียกใช้ของเอฟเฟกต์ [`EffectTriggerType`](../../effecttriggertype) |

### ค่าที่คืนค่า

ออบเจ็กต์เอฟเฟกต์ใหม่ [`IEffect`](../../ieffect)

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IEffect](../../ieffect)
* อินเทอร์เฟซ [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* อินเทอร์เฟซ [ISequence](../../isequence)
* เนมสเปซ [Aspose.Slides.Animation](../../isequence)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

เพิ่มเอฟเฟกต์แอนิเมชันใหม่สำหรับองค์ประกอบในประเภทหรือชุดข้อมูลของแผนภูมิไปยังส่วนท้ายของลำดับ

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| chart | IChart | ออบเจ็กต์ Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | ชนิดของเอฟเฟกต์แอนิเมชัน [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | ดัชนีชุดข้อมูลของแผนภูมิ Int32 |
| categoriesIndex | Int32 | ดัชนีประเภท Int32 |
| effectType | EffectType | ชนิดของเอฟเฟกต์แอนิเมชัน [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | ชนิดย่อยของเอฟเฟกต์แอนิเมชัน [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | ประเภทการเรียกใช้ของเอฟเฟกต์ [`EffectTriggerType`](../../effecttriggertype) |

### ค่าที่คืนค่า

ออบเจ็กต์เอฟเฟกต์ใหม่ [`IEffect`](../../ieffect)

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IEffect](../../ieffect)
* อินเทอร์เฟซ [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* อินเทอร์เฟซ [ISequence](../../isequence)
* เนมสเปซ [Aspose.Slides.Animation](../../isequence)
* แอสเซมบลี [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->