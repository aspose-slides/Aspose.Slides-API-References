---
title: AddEffect
second_title: Aspose.Sildes για .NET API Αναφορά
description: Προσθέτει νέο εφέ στο τέλος της ακολουθίας.
type: docs
weight: 40
url: /el/aspose.slides.animation/sequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Προσθέτει νέο εφέ στο τέλος της ακολουθίας.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | IShape | Αντικείμενο Shape [`IShape`](../../../aspose.slides/ishape) για προσθήκη εφέ |
| effectType | EffectType | Τύπος εφέ κίνησης [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Υποτυποί εφέ κίνησης [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Τύπος ενεργοποίησης εφέ [`EffectTriggerType`](../../effecttriggertype) |

### Τιμή Επιστροφής

Νέο αντικείμενο εφέ [`IEffect`](../../ieffect)

### Δείτε επίσης

* διασύνδεση [IEffect](../../ieffect)
* διασύνδεση [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* κλάση [Sequence](../../sequence)
* χώρος ονομάτων [Aspose.Slides.Animation](../../sequence)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Προσθέτει νέο εφέ κίνησης για την παράγραφο στο τέλος της ακολουθίας.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| paragraph | IParagraph | Αντικείμενο Paragraph [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Τύπος εφέ κίνησης [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Υποτυποί εφέ κίνησης [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Τύπος ενεργοποίησης εφέ [`EffectTriggerType`](../../effecttriggertype) |

### Τιμή Επιστροφής

Νέο αντικείμενο εφέ [`IEffect`](../../ieffect)

### Παραδείγματα

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // επιλέξτε την παράγραφο για προσθήκη εφέ
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // προσθέστε εφέ κίνησης Fly στην επιλεγμένη παράγραφο
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### Δείτε επίσης

* διασύνδεση [IEffect](../../ieffect)
* διασύνδεση [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* κλάση [Sequence](../../sequence)
* χώρος ονομάτων [Aspose.Slides.Animation](../../sequence)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Προσθέτει το νέο εφέ κίνησης γραφήματος για την κατηγορία ή τη σειρά στο τέλος της ακολουθίας.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chart | IChart | Αντικείμενο Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Τύπος εφέ κίνησης [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Δείκτης Int32 |
| effectType | EffectType | Τύπος εφέ κίνησης [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Υποτυποί εφέ κίνησης [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Τύπος ενεργοποίησης εφέ [`EffectTriggerType`](../../effecttriggertype) |

### Τιμή Επιστροφής

Νέο αντικείμενο εφέ [`IEffect`](../../ieffect)

### Δείτε επίσης

* διασύνδεση [IEffect](../../ieffect)
* διασύνδεση [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* κλάση [Sequence](../../sequence)
* χώρος ονομάτων [Aspose.Slides.Animation](../../sequence)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Προσθέτει το νέο εφέ κίνησης γραφήματος για στοιχεία στην κατηγορία ή τη σειρά στο τέλος της ακολουθίας.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chart | IChart | Αντικείμενο Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Τύπος εφέ κίνησης [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Δείκτης σειράς γραφήματος Int32 |
| categoriesIndex | Int32 | Δείκτης κατηγορίας Int32 |
| effectType | EffectType | Τύπος εφέ κίνησης [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Υποτυποί εφέ κίνησης [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Τύπος ενεργοποίησης εφέ [`EffectTriggerType`](../../effecttriggertype) |

### Τιμή Επιστροφής

Νέο αντικείμενο εφέ [`IEffect`](../../ieffect)

### Δείτε επίσης

* διασύνδεση [IEffect](../../ieffect)
* διασύνδεση [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* κλάση [Sequence](../../sequence)
* χώρος ονομάτων [Aspose.Slides.Animation](../../sequence)
* συναρμολόγηση [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->