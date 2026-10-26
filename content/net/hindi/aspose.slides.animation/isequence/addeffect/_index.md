---
title: AddEffect
second_title: Aspose.Sildes for .NET API संदर्भ
description: सीक्वेंस के अंत में नया इफ़ेक्ट जोड़ें।
type: docs
weight: 50
url: /hi/aspose.slides.animation/isequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

सीक्वेंस के अंत में नया इफ़ेक्ट जोड़ें।

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shape | IShape | इफ़ेक्ट जोड़ने के लिए Shape ऑब्जेक्ट [`IShape`](../../../aspose.slides/ishape) |
| effectType | EffectType | एनिमेशन इफ़ेक्ट का प्रकार [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | एनिमेशन इफ़ेक्ट के उपप्रकार [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | इफ़ेक्ट का ट्रिगर प्रकार [`EffectTriggerType`](../../effecttriggertype) |

### रिटर्न वैल्यू

नया इफ़ेक्ट ऑब्जेक्ट [`IEffect`](../../ieffect)

### संबंधित देखें

* इंटरफ़ेस [IEffect](../../ieffect)
* इंटरफ़ेस [IShape](../../../aspose.slides/ishape)
* एनम [EffectType](../../effecttype)
* एनम [EffectSubtype](../../effectsubtype)
* एनम [EffectTriggerType](../../effecttriggertype)
* इंटरफ़ेस [ISequence](../../isequence)
* नामस्थान [Aspose.Slides.Animation](../../isequence)
* असेंबली [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

पैराग्राफ के लिए नया एनिमेशन इफ़ेक्ट सीक्वेंस के अंत में जोड़ें।

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| paragraph | IParagraph | Paragraph ऑब्जेक्ट [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | एनिमेशन इफ़ेक्ट का प्रकार [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | एनिमेशन इफ़ेक्ट के उपप्रकार [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | इफ़ेक्ट का ट्रिगर प्रकार [`EffectTriggerType`](../../effecttriggertype) |

### रिटर्न वैल्यू

नया इफ़ेक्ट ऑब्जेक्ट [`IEffect`](../../ieffect)

### उदाहरण

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // प्रभाव जोड़ने के लिए पैराग्राफ चुनें
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // चयनित पैराग्राफ में Fly एनीमेशन इफ़ेक्ट जोड़ें
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### संबंधित देखें

* इंटरफ़ेस [IEffect](../../ieffect)
* इंटरफ़ेस [IParagraph](../../../aspose.slides/iparagraph)
* एनम [EffectType](../../effecttype)
* एनम [EffectSubtype](../../effectsubtype)
* एनम [EffectTriggerType](../../effecttriggertype)
* इंटरफ़ेस [ISequence](../../isequence)
* नामस्थान [Aspose.Slides.Animation](../../isequence)
* असेंबली [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

कैटेगरी या सीरीज़ के लिए नया चार्ट एनिमेशन इफ़ेक्ट सीक्वेंस के अंत में जोड़ता है।

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chart | IChart | Chart ऑब्जेक्ट [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | एनिमेशन इफ़ेक्ट का प्रकार [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | इंडेक्स Int32 |
| effectType | EffectType | एनिमेशन इफ़ेक्ट का प्रकार [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | एनिमेशन इफ़ेक्ट के उपप्रकार [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | इफ़ेक्ट का ट्रिगर प्रकार [`EffectTriggerType`](../../effecttriggertype) |

### रिटर्न वैल्यू

नया इफ़ेक्ट ऑब्जेक्ट [`IEffect`](../../ieffect)

### संबंधित देखें

* इंटरफ़ेस [IEffect](../../ieffect)
* इंटरफ़ेस [IChart](../../../aspose.slides.charts/ichart)
* एनम [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* एनम [EffectType](../../effecttype)
* एनम [EffectSubtype](../../effectsubtype)
* एनम [EffectTriggerType](../../effecttriggertype)
* इंटरफ़ेस [ISequence](../../isequence)
* नामस्थान [Aspose.Slides.Animation](../../isequence)
* असेंबली [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

कैटेगरी या सीरीज़ के तत्वों के लिए नया चार्ट एनिमेशन इफ़ेक्ट सीक्वेंस के अंत में जोड़ता है।

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chart | IChart | Chart ऑब्जेक्ट [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | एनिमेशन इफ़ेक्ट का प्रकार [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | चार्ट सीरीज़ का इंडेक्स Int32 |
| categoriesIndex | Int32 | कैटेगरी का इंडेक्स Int32 |
| effectType | EffectType | एनिमेशन इफ़ेक्ट का प्रकार [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | एनिमेशन इफ़ेक्ट के उपप्रकार [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | इफ़ेक्ट का ट्रिगर प्रकार [`EffectTriggerType`](../../effecttriggertype) |

### रिटर्न वैल्यू

नया इफ़ेक्ट ऑब्जेक्ट [`IEffect`](../../ieffect)

### संबंधित देखें

* इंटरफ़ेस [IEffect](../../ieffect)
* इंटरफ़ेस [IChart](../../../aspose.slides.charts/ichart)
* एनम [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* एनम [EffectType](../../effecttype)
* एनम [EffectSubtype](../../effectsubtype)
* एनम [EffectTriggerType](../../effecttriggertype)
* इंटरफ़ेस [ISequence](../../isequence)
* नामस्थान [Aspose.Slides.Animation](../../isequence)
* असेंबली [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->