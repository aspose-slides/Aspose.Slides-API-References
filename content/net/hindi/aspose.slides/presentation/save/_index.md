---
title: Save
second_title: Aspose.Sildes for .NET API संदर्भ
description: निर्दिष्ट प्रारूप में फ़ाइल में प्रस्तुति की सभी स्लाइड्स को सहेजता है।
type: docs
weight: 390
url: /hi/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट प्रारूप में फ़ाइल में सहेजता है।

```csharp
public void Save(string fname, SaveFormat format)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | String | बनाई गई फ़ाइल का पथ। |
| format | SaveFormat | निर्यात किए गए डेटा का प्रारूप। |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* क्‍लास [Presentation](../../presentation)
* नेमस्पेस [Aspose.Slides](../../presentation)
* असेंब्लि [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट प्रारूप में स्ट्रीम में सहेजता है।

```csharp
public void Save(Stream stream, SaveFormat format)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | आउटपुट स्ट्रीम। |
| format | SaveFormat | निर्यात किए गए डेटा का प्रारूप। |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* क्‍लास [Presentation](../../presentation)
* नेमस्पेस [Aspose.Slides](../../presentation)
* असेंब्लि [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* क्‍लास [Presentation](../../presentation)
* नेमस्पेस [Aspose.Slides](../../presentation)
* असेंब्लि [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

निर्दिष्ट प्रारूप में अतिरिक्त विकल्पों के साथ स्ट्रीम में प्रस्तुति की सभी स्लाइड्स को सहेजता है।

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | आउटपुट स्ट्रीम। |
| format | SaveFormat | निर्यात किए गए डेटा का प्रारूप। |
| options | ISaveOptions | अतिरिक्त प्रारूप विकल्प। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| NotSupportedException | यदि आप एन्क्रिप्टेड फ़ाइल को Office 2007-2010 के अलावा किसी प्रारूप में सहेजने का प्रयास करते हैं |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* क्‍लास [Presentation](../../presentation)
* नेमस्पेस [Aspose.Slides](../../presentation)
* असेंब्लि [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

प्रस्तुति की सभी स्लाइड्स को XAML मार्कअप का प्रतिनिधित्व करने वाली फ़ाइलों के सेट में सहेजता है।

```csharp
public void Save(IXamlOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | IXamlOptions | XAML प्रारूप विकल्प। |

### उदाहरण

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### संबंधित देखें

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* क्‍लास [Presentation](../../presentation)
* नेमस्पेस [Aspose.Slides](../../presentation)
* असेंब्लि [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

निर्दिष्ट स्लाइड्स को पृष्ठ संख्या बनाए रखते हुए फ़ाइल में सहेजता है।

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | String | बनाई गई फ़ाइल का पथ। |
| slides | Int32[] | स्लाइड स्थितियों की सरणी, 1 से शुरू। |
| format | SaveFormat | निर्यात किए गए डेटा का प्रारूप। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब stream या slides पैरामीटर null हो। |
| ArgumentOutOfRangeException | जब slides पैरामीटर में गलत पृष्ठ संख्याएँ हों। |
| InvalidOperationException | जब असमर्थित SaveFormat उपयोग किया गया हो, जैसे PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP। |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* क्‍लास [Presentation](../../presentation)
* नेमस्पेस [Aspose.Slides](../../presentation)
* असेंब्लि [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

निर्दिष्ट स्लाइड्स को पृष्ठ संख्या बनाए रखते हुए फ़ाइल में अतिरिक्त विकल्पों के साथ सहेजता है।

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | String | बनाई गई फ़ाइल का पथ। |
| slides | Int32[] | स्लाइड स्थितियों की सरणी, 1 से शुरू। |
| format | SaveFormat | निर्यात किए गए डेटा का प्रारूप। |
| options | ISaveOptions | अतिरिक्त प्रारूप विकल्प। |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* क्‍लास [Presentation](../../presentation)
* नेमस्पेस [Aspose.Slides](../../presentation)
* असेंब्लि [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

निर्दिष्ट स्लाइड्स को पृष्ठ संख्या बनाए रखते हुए स्ट्रीम में सहेजता है।

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | आउटपुट स्ट्रीम। |
| slides | Int32[] | स्लाइड स्थितियों की सरणी, 1 से शुरू। |
| format | SaveFormat | निर्यात किए गए डेटा का प्रारूप। |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* क्‍लास [Presentation](../../presentation)
* नेमस्पेस [Aspose.Slides](../../presentation)
* असेंब्लि [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

निर्दिष्ट स्लाइड्स को पृष्ठ संख्या बनाए रखते हुए स्ट्रीम में अतिरिक्त विकल्पों के साथ सहेजता है।

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | आउटपुट स्ट्रीम। |
| slides | Int32[] | स्लाइड स्थितियों की सरणी, 1 से शुरू। |
| format | SaveFormat | निर्यात किए गए डेटा का प्रारूप। |
| options | ISaveOptions | अतिरिक्त प्रारूप विकल्प। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब stream या slides पैरामीटर null हो। |
| ArgumentOutOfRangeException | जब slides पैरामीटर में गलत पृष्ठ संख्याएँ हों। |
| InvalidOperationException | जब असमर्थित SaveFormat उपयोग किया गया हो, जैसे PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP। |

### उदाहरण

निम्न उदाहरण दिखाता है कि PowerPoint को PNG में कैसे परिवर्तित करें।

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail().Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

निम्न उदाहरण दिखाता है कि कस्टम आयामों के साथ PowerPoint को PNG में कैसे परिवर्तित करें।

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    float scaleX = 2f;
    float scaleY = 2f;
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(scaleX, scaleY).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

निम्न उदाहरण दिखाता है कि कस्टम आकार के साथ PowerPoint को PNG में कैसे परिवर्तित करें।

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    Size size = new Size(960, 720);
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(size).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* क्‍लास [Presentation](../../presentation)
* नेमस्पेस [Aspose.Slides](../../presentation)
* असेंब्लि [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->