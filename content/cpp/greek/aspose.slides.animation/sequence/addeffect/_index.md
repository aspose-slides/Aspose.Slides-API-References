---
title: AddEffect()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει νέο εφέ στο τέλος της ακολουθίας.
type: docs
weight: 157
url: /el/aspose.slides.animation/sequence/addeffect/
---
## Sequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) μέθοδος

Προσθέτει νέο εφέ στο τέλος της ακολουθίας.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) αντικείμενο [IShape](../../../aspose.slides/ishape/) για την προσθήκη ενός εφέ |
| effectType | [EffectType](../../effecttype/) | Τύπος εφέ κίνησης [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Υποτύποι εφέ κίνησης [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Τύπος ενεργοποίησης εφέ [EffectTriggerType](../../effecttriggertype/) |

### Τιμή Επιστροφής

Νέο αντικείμενο εφέ [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) μέθοδος

Προσθέτει νέο εφέ κίνησης για παράγραφο στο τέλος της ακολουθίας.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) αντικείμενο [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | Τύπος εφέ κίνησης [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Υποτύποι εφέ κίνησης [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Τύπος ενεργοποίησης εφέ [EffectTriggerType](../../effecttriggertype/) |

### Τιμή Επιστροφής

Νέο αντικείμενο εφέ [IEffect](../../ieffect/)

## Παρατηρήσεις

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// επιλέξτε παράγραφο για προσθήκη εφέ
auto autoShape = System::ExplicitCast<Aspose::Slides::IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// προσθέστε το εφέ κίνησης Fly στην επιλεγμένη παράγραφο
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Aspose::Slides::Animation::EffectType::Fly, 
     Aspose::Slides::Animation::EffectSubtype::Left, 
     Aspose::Slides::Animation::EffectTriggerType::OnClick);
```

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) μέθοδος

Προσθέτει νέο εφέ κίνησης διαγράμματος για κατηγορία ή σειρά στο τέλος της ακολουθίας.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | αντικείμενο Chart [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | Τύπος εφέ κίνησης [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | Δείκτης **int32_t** |
| effectType | [EffectType](../../effecttype/) | Τύπος εφέ κίνησης [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Υποτύποι εφέ κίνησης [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Τύπος ενεργοποίησης εφέ [EffectTriggerType](../../effecttriggertype/) |

### Τιμή Επιστροφής

Νέο αντικείμενο εφέ [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) μέθοδος

Προσθέτει νέο εφέ κίνησης διαγράμματος για στοιχεία σε κατηγορία ή σειρά στο τέλος της ακολουθίας.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | αντικείμενο Chart [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | Τύπος εφέ κίνησης [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | Δείκτης σειράς διαγράμματος **int32_t** |
| categoriesIndex | **int32_t** | Δείκτης κατηγορίας **int32_t** |
| effectType | [EffectType](../../effecttype/) | Τύπος εφέ κίνησης [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Υποτύποι εφέ κίνησης [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Τύπος ενεργοποίησης εφέ [EffectTriggerType](../../effecttriggertype/) |

### Τιμή Επιστροφής

Νέο αντικείμενο εφέ [IEffect](../../ieffect/)

## Δείτε Επίσης

* Απαρίθμηση [EffectType](../../effecttype/)
* Απαρίθμηση [EffectSubtype](../../effectsubtype/)
* Απαρίθμηση [EffectTriggerType](../../effecttriggertype/)
* Απαρίθμηση [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Απαρίθμηση [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IEffect](../../ieffect/)
* Κλάση [IShape](../../../aspose.slides/ishape/)
* Κλάση [Sequence](../)
* Κλάση [IParagraph](../../../aspose.slides/iparagraph/)
* Κλάση [IChart](../../../aspose.slides.charts/ichart/)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)