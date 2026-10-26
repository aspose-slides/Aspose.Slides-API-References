---
title: AddEffect
second_title: Referensi API Aspose.Sildes untuk .NET
description: Menambahkan efek baru ke akhir urutan.
type: docs
weight: 50
url: /id/aspose.slides.animation/isequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Menambahkan efek baru ke akhir urutan.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shape | IShape | Objek Shape [`IShape`](../../../aspose.slides/ishape) untuk menambahkan efek |
| effectType | EffectType | Tipe efek animasi [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipe efek animasi [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipe pemicu efek [`EffectTriggerType`](../../effecttriggertype) |

### Nilai Kembalian

Objek efek baru [`IEffect`](../../ieffect)

### Lihat Juga

* antarmuka [IEffect](../../ieffect)
* antarmuka [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* antarmuka [ISequence](../../isequence)
* ruang nama [Aspose.Slides.Animation](../../isequence)
* rakitan [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Menambahkan efek animasi baru untuk paragraf ke akhir urutan.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| paragraph | IParagraph | Objek Paragraph [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Tipe efek animasi [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipe efek animasi [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipe pemicu efek [`EffectTriggerType`](../../effecttriggertype) |

### Nilai Kembalian

Objek efek baru [`IEffect`](../../ieffect)

### Contoh

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // pilih paragraf untuk menambahkan efek
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // tambahkan efek animasi Fly ke paragraf yang dipilih
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### Lihat Juga

* antarmuka [IEffect](../../ieffect)
* antarmuka [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* antarmuka [ISequence](../../isequence)
* ruang nama [Aspose.Slides.Animation](../../isequence)
* rakitan [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Menambahkan efek animasi chart baru untuk kategori atau seri ke akhir urutan.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chart | IChart | Objek Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Tipe efek animasi [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Indeks Int32 |
| effectType | EffectType | Tipe efek animasi [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipe efek animasi [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipe pemicu efek [`EffectTriggerType`](../../effecttriggertype) |

### Nilai Kembalian

Objek efek baru [`IEffect`](../../ieffect)

### Lihat Juga

* antarmuka [IEffect](../../ieffect)
* antarmuka [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* antarmuka [ISequence](../../isequence)
* ruang nama [Aspose.Slides.Animation](../../isequence)
* rakitan [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Menambahkan efek animasi chart baru untuk elemen dalam kategori atau seri ke akhir urutan.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chart | IChart | Objek Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Tipe efek animasi [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Indeks seri chart Int32 |
| categoriesIndex | Int32 | Indeks kategori Int32 |
| effectType | EffectType | Tipe efek animasi [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipe efek animasi [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipe pemicu efek [`EffectTriggerType`](../../effecttriggertype) |

### Nilai Kembalian

Objek efek baru [`IEffect`](../../ieffect)

### Lihat Juga

* antarmuka [IEffect](../../ieffect)
* antarmuka [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* antarmuka [ISequence](../../isequence)
* ruang nama [Aspose.Slides.Animation](../../isequence)
* rakitan [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->