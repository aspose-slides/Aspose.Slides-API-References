---
title: Save
second_title: Aspose.Sildes .NET के लिए API संदर्भ
description: प्रस्तुति की सभी स्लाइडों को निर्दिष्ट फ़ॉर्मेट के साथ फ़ाइल में सहेजता है।
type: docs
weight: 390
url: /hi/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

प्रस्तुति की सभी स्लाइडों को निर्दिष्ट फ़ॉर्मेट के साथ फ़ाइल में सहेजता है।

```csharp
public void Save(string fname, SaveFormat format)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | String | निर्मित फ़ाइल का पथ। |
| format | SaveFormat | निर्यातित डेटा का फ़ॉर्मेट। |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

प्रस्तुति की सभी स्लाइडों को निर्दिष्ट फ़ॉर्मेट में स्ट्रीम में सहेजता है।

```csharp
public void Save(Stream stream, SaveFormat format)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | आउटपुट स्ट्रीम। |
| format | SaveFormat | निर्यातित डेटा का फ़ॉर्मेट। |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

प्रस्तुति की सभी स्लाइडों को निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ फ़ाइल में सहेजता है।

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | String | निर्मित फ़ाइल का पथ। |
| format | SaveFormat | निर्यातित डेटा का फ़ॉर्मेट। |
| options | ISaveOptions | अतिरिक्त फ़ॉर्मेट विकल्प। |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

प्रस्तुति की सभी स्लाइडों को निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ स्ट्रीम में सहेजता है।

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | आउटपुट स्ट्रीम। |
| format | SaveFormat | निर्यातित डेटा का फ़ॉर्मेट। |
| options | ISaveOptions | अतिरिक्त फ़ॉर्मेट विकल्प। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| NotSupportedException | यदि आप एन्क्रिप्टेड फ़ाइल को Office 2007-2010 के अलावा किसी फ़ॉर्मेट में सहेजने का प्रयास करते हैं |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

निर्दिष्ट स्लाइडों को प्रस्तुति से फ़ाइल में निर्दिष्ट फ़ॉर्मेट के साथ सहेजता है।

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | String | निर्मित फ़ाइल का पथ। |
| slides | Int32[] | स्लाइड स्थितियों की सरणी, 1 से शुरू। |
| format | SaveFormat | निर्यातित डेटा का फ़ॉर्मेट। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | जब स्ट्रीम या स्लाइड्स पैरामीटर null हो। |
| ArgumentOutOfRangeException | जब स्लाइड्स पैरामीटर में गलत पृष्ठ संख्याएँ हों। |
| InvalidOperationException | जब असमर्थित SaveFormat का उपयोग किया जाता है, जैसे PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP। |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

निर्दिष्ट स्लाइडों को प्रस्तुति से फ़ाइल में निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ सहेजता है।

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | String | निर्मित फ़ाइल का पथ। |
| slides | Int32[] | स्लाइड स्थितियों की सरणी, 1 से शुरू। |
| format | SaveFormat | निर्यातित डेटा का फ़ॉर्मेट। |
| options | ISaveOptions | अतिरिक्त फ़ॉर्मेट विकल्प। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | जब स्ट्रीम या स्लाइड्स पैरामीटर null हो। |
| ArgumentOutOfRangeException | जब स्लाइड्स पैरामीटर में गलत पृष्ठ संख्याएँ हों। |
| InvalidOperationException | जब असमर्थित SaveFormat का उपयोग किया जाता है, जैसे PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP। |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

निर्दिष्ट स्लाइडों को प्रस्तुति से स्ट्रीम में निर्दिष्ट फ़ॉर्मेट के साथ सहेजता है।

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | आउटपुट स्ट्रीम। |
| slides | Int32[] | स्लाइड स्थितियों की सरणी, 1 से शुरू। |
| format | SaveFormat | निर्यातित डेटा का फ़ॉर्मेट। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | जब स्ट्रीम या स्लाइड्स पैरामीटर null हो। |
| ArgumentOutOfRangeException | जब स्लाइड्स पैरामीटर में गलत पृष्ठ संख्याएँ हों। |
| InvalidOperationException | जब असमर्थित SaveFormat का उपयोग किया जाता है, जैसे PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP। |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

निर्दिष्ट स्लाइडों को प्रस्तुति से स्ट्रीम में निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ सहेजता है।

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | आउटपुट स्ट्रीम। |
| slides | Int32[] | स्लाइड स्थितियों की सरणी, 1 से शुरू। |
| format | SaveFormat | निर्यातित डेटा का फ़ॉर्मेट। |
| options | ISaveOptions | अतिरिक्त फ़ॉर्मेट विकल्प। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | जब स्ट्रीम या स्लाइड्स पैरामीटर null हो। |
| ArgumentOutOfRangeException | जब स्लाइड्स पैरामीटर में गलत पृष्ठ संख्याएँ हों। |
| InvalidOperationException | जब असमर्थित SaveFormat का उपयोग किया जाता है, जैसे PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP। |

### संबंधित देखें

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

प्रस्तुति की सभी स्लाइडों को XAML मार्कअप का प्रतिनिधित्व करने वाली फ़ाइलों के सेट में सहेजता है।

```csharp
public void Save(IXamlOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | IXamlOptions | XAML फ़ॉर्मेट विकल्प। |

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
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->