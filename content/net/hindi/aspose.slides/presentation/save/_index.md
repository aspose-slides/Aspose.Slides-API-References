---
title: Save
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट स्वरूप के साथ फ़ाइल में सहेजता है।
type: docs
weight: 400
url: /hi/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट स्वरूप के साथ फ़ाइल में सहेजता है।

```csharp
public void Save(string fname, SaveFormat format)
```

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | String | निर्मित फ़ाइल का पथ। |
| format | SaveFormat | निर्यातित डेटा का स्वरूप। |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* क्लास [Presentation](../../presentation)
* नेमस्पेस [Aspose.Slides](../../presentation)
* असेंबली [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट स्वरूप में Stream में सहेजता है।

```csharp
public void Save(Stream stream, SaveFormat format)
```

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | आउटपुट Stream। |
| format | SaveFormat | निर्यातित डेटा का स्वरूप। |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* क्लास [Presentation](../../presentation)
* नेमस्पेस [Aspose.Slides](../../presentation)
* असेंबली [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* इंटरफ़ेस [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* क्लास [Presentation](../../presentation)
* नेमस्पेस [Aspose.Slides](../../presentation)
* असेंबली [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट स्वरूप में Stream में अतिरिक्त विकल्पों के साथ सहेजता है।

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | आउटपुट Stream। |
| format | SaveFormat | निर्यातित डेटा का स्वरूप। |
| options | ISaveOptions | अतिरिक्त स्वरूप विकल्प। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| NotSupportedException | यदि आप एन्क्रिप्टेड फ़ाइल को Office 2007-2010 के अलावा किसी स्वरूप में सहेजने की कोशिश करते हैं |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* इंटरफ़ेस [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* क्लास [Presentation](../../presentation)
* नेमस्पेस [Aspose.Slides](../../presentation)
* असेंबली [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

प्रस्तुति की सभी स्लाइड्स को XAML मार्कअप दर्शाने वाली फ़ाइलों के सेट में सहेजता है।

```csharp
public void Save(IXamlOptions options)
```

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | IXamlOptions | XAML स्वरूप विकल्प। |

### उदाहरण

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### संबंधित देखें

* इंटरफ़ेस [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* क्लास [Presentation](../../presentation)
* नेमस्पेस [Aspose.Slides](../../presentation)
* असेंबली [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

निर्दिष्ट स्लाइड्स को प्रस्तुति के फ़ाइल में निर्दिष्ट स्वरूप के साथ पृष्ठ संख्या बनाए रखते हुए सहेजता है।

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | String | निर्मित फ़ाइल का पथ। |
| slides | Int32[] | स्लाइड स्थितियों का सरणी, 1 से शुरू। |
| format | SaveFormat | निर्यातित डेटा का स्वरूप। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | जब stream या slides पैरामीटर शून्य (null) हो। |
| ArgumentOutOfRangeException | जब slides पैरामीटर में गलत पृष्ठ संख्याएँ हों। |
| InvalidOperationException | जब असमर्थित SaveFormat का उपयोग किया जाता है, जैसे PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP। |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* क्लास [Presentation](../../presentation)
* नेमस्पेस [Aspose.Slides](../../presentation)
* असेंबली [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

निर्दिष्ट स्लाइड्स को प्रस्तुति के फ़ाइल में निर्दिष्ट स्वरूप के साथ पृष्ठ संख्या बनाए रखते हुए अतिरिक्त विकल्पों के साथ सहेजता है।

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | String | निर्मित फ़ाइल का पथ। |
| slides | Int32[] | स्लाइड स्थितियों का सरणी, 1 से शुरू। |
| format | SaveFormat | निर्यातित डेटा का स्वरूप। |
| options | ISaveOptions | अतिरिक्त स्वरूप विकल्प। |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* इंटरफ़ेस [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* क्लास [Presentation](../../presentation)
* नेमस्पेस [Aspose.Slides](../../presentation)
* असेंबली [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

निर्दिष्ट स्लाइड्स को प्रस्तुति के Stream में निर्दिष्ट स्वरूप के साथ पृष्ठ संख्या बनाए रखते हुए सहेजता है।

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | आउटपुट Stream। |
| slides | Int32[] | स्लाइड स्थितियों का सरणी, 1 से शुरू। |
| format | SaveFormat | निर्यातित डेटा का स्वरूप। |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* क्लास [Presentation](../../presentation)
* नेमस्पेस [Aspose.Slides](../../presentation)
* असेंबली [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

निर्दिष्ट स्लाइड्स को प्रस्तुति के Stream में निर्दिष्ट स्वरूप के साथ पृष्ठ संख्या बनाए रखते हुए अतिरिक्त विकल्पों के साथ सहेजता है।

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | आउटपुट Stream। |
| slides | Int32[] | स्लाइड स्थितियों का सरणी, 1 से शुरू। |
| format | SaveFormat | निर्यातित डेटा का स्वरूप। |
| options | ISaveOptions | अतिरिक्त स्वरूप विकल्प। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | जब stream या slides पैरामीटर शून्य (null) हो। |
| ArgumentOutOfRangeException | जब slides पैरामीटर में गलत पृष्ठ संख्याएँ हों। |
| InvalidOperationException | जब असमर्थित SaveFormat का उपयोग किया जाता है, जैसे PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP। |

### उदाहरण

निम्न उदाहरण दिखाता है कि PowerPoint को PNG में कैसे परिवर्तित किया जाए।

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

निम्न उदाहरण दिखाता है कि कस्टम आयामों के साथ PowerPoint को PNG में कैसे परिवर्तित किया जाए।

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

निम्न उदाहरण दिखाता है कि कस्टम आकार के साथ PowerPoint को PNG में कैसे परिवर्तित किया जाए।

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
* इंटरफ़ेस [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* क्लास [Presentation](../../presentation)
* नेमस्पेस [Aspose.Slides](../../presentation)
* असेंबली [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->