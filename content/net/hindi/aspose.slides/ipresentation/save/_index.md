---
title: Save
second_title: Aspose.Sildes for .NET API संदर्भ
description: निर्दिष्ट प्रारूप के साथ प्रस्तुति की सभी स्लाइड्स को फ़ाइल में सहेजता है।
type: docs
weight: 380
url: /hi/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

निर्दिष्ट प्रारूप के साथ प्रस्तुति की सभी स्लाइड्स को फ़ाइल में सहेजता है।

```csharp
public void Save(string fname, SaveFormat format)
```

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | SaveFormat | Format of the exported data. |

### संबंधित देखें

* एन्युम [SaveFormat](../../../aspose.slides.export/saveformat)
* इंटरफ़ेस [IPresentation](../../ipresentation)
* नामस्थान [Aspose.Slides](../../ipresentation)
* असेंबली [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

निर्दिष्ट प्रारूप में प्रस्तुति की सभी स्लाइड्स को स्ट्रीम में सहेजता है।

```csharp
public void Save(Stream stream, SaveFormat format)
```

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |

### संबंधित देखें

* एन्युम [SaveFormat](../../../aspose.slides.export/saveformat)
* इंटरफ़ेस [IPresentation](../../ipresentation)
* नामस्थान [Aspose.Slides](../../ipresentation)
* असेंबली [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

निर्दिष्ट प्रारूप और अतिरिक्त विकल्पों के साथ प्रस्तुति की सभी स्लाइड्स को फ़ाइल में सहेजता है।

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### संबंधित देखें

* एन्युम [SaveFormat](../../../aspose.slides.export/saveformat)
* इंटरफ़ेस [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* इंटरफ़ेस [IPresentation](../../ipresentation)
* नामस्थान [Aspose.Slides](../../ipresentation)
* असेंबली [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

निर्दिष्ट प्रारूप और अतिरिक्त विकल्पों के साथ प्रस्तुति की सभी स्लाइड्स को स्ट्रीम में सहेजता है।

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |

### संबंधित देखें

* एन्युम [SaveFormat](../../../aspose.slides.export/saveformat)
* इंटरफ़ेस [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* इंटरफ़ेस [IPresentation](../../ipresentation)
* नामस्थान [Aspose.Slides](../../ipresentation)
* असेंबली [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

निर्दिष्ट प्रारूप के साथ प्रस्तुति की चयनित स्लाइड्स को फ़ाइल में सहेजता है।

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### संबंधित देखें

* एन्युम [SaveFormat](../../../aspose.slides.export/saveformat)
* इंटरफ़ेस [IPresentation](../../ipresentation)
* नामस्थान [Aspose.Slides](../../ipresentation)
* असेंबली [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

निर्दिष्ट प्रारूप और अतिरिक्त विकल्पों के साथ प्रस्तुति की चयनित स्लाइड्स को फ़ाइल में सहेजता है।

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### संबंधित देखें

* एन्युम [SaveFormat](../../../aspose.slides.export/saveformat)
* इंटरफ़ेस [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* इंटरफ़ेस [IPresentation](../../ipresentation)
* नामस्थान [Aspose.Slides](../../ipresentation)
* असेंबली [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

निर्दिष्ट प्रारूप में प्रस्तुति की चयनित स्लाइड्स को स्ट्रीम में सहेजता है।

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### संबंधित देखें

* एन्युम [SaveFormat](../../../aspose.slides.export/saveformat)
* इंटरफ़ेस [IPresentation](../../ipresentation)
* नामस्थान [Aspose.Slides](../../ipresentation)
* असेंबली [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

निर्दिष्ट प्रारूप और अतिरिक्त विकल्पों के साथ प्रस्तुति की चयनित स्लाइड्स को स्ट्रीम में सहेजता है।

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### संबंधित देखें

* एन्युम [SaveFormat](../../../aspose.slides.export/saveformat)
* इंटरफ़ेस [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* इंटरफ़ेस [IPresentation](../../ipresentation)
* नामस्थान [Aspose.Slides](../../ipresentation)
* असेंबली [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

प्रस्तुति की सभी स्लाइड्स को XAML मार्कअप दर्शाने वाली फाइलों के सेट में सहेजता है।

```csharp
public void Save(IXamlOptions options)
```

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | IXamlOptions | The XAML format options. |

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
* इंटरफ़ेस [IPresentation](../../ipresentation)
* नामस्थान [Aspose.Slides](../../ipresentation)
* असेंबली [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->