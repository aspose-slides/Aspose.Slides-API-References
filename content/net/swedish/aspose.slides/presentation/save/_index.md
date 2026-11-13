---
title: Save
second_title: Aspose.Sildes för .NET API-referens
description: Sparar alla bilder i en presentation till en fil med det angivna formatet.
type: docs
weight: 400
url: /sv/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

Sparar alla bilder i en presentation till en fil med det angivna formatet.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | SaveFormat | Format of the exported data. |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* klass [Presentation](../../presentation)
* namnutrymme [Aspose.Slides](../../presentation)
* samling [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Sparar alla bilder i en presentation till en ström i det angivna formatet.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* klass [Presentation](../../presentation)
* namnutrymme [Aspose.Slides](../../presentation)
* samling [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* gränssnitt [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* klass [Presentation](../../presentation)
* namnutrymme [Aspose.Slides](../../presentation)
* samling [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Sparar alla bilder i en presentation till en ström i det angivna formatet och med ytterligare alternativ.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Undantag

| undantag | villkor |
| --- | --- |
| NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* gränssnitt [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* klass [Presentation](../../presentation)
* namnutrymme [Aspose.Slides](../../presentation)
* samling [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Sparar alla bilder i en presentation till en uppsättning filer som representerar XAML-markup.

```csharp
public void Save(IXamlOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | IXamlOptions | The XAML format options. |

### Exempel

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Se även

* gränssnitt [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* klass [Presentation](../../presentation)
* namnutrymme [Aspose.Slides](../../presentation)
* samling [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Sparar angivna bilder i en presentation till en fil med det angivna formatet och behåller sidnumren.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* klass [Presentation](../../presentation)
* namnutrymme [Aspose.Slides](../../presentation)
* samling [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Sparar angivna bilder i en presentation till en fil med det angivna formatet och behåller sidnumren.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* gränssnitt [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* klass [Presentation](../../presentation)
* namnutrymme [Aspose.Slides](../../presentation)
* samling [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Sparar angivna bilder i en presentation till en ström i det angivna formatet och behåller sidnumren.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* klass [Presentation](../../presentation)
* namnutrymme [Aspose.Slides](../../presentation)
* samling [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Sparar angivna bilder i en presentation till en ström i det angivna formatet och behåller sidnumren.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Exempel

Följande exempel visar hur man konverterar PowerPoint till PNG.

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

Följande exempel visar hur man konverterar PowerPoint till PNG med anpassade dimensioner.

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

Följande exempel visar hur man konverterar PowerPoint till PNG med anpassad storlek.

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

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* gränssnitt [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* klass [Presentation](../../presentation)
* namnutrymme [Aspose.Slides](../../presentation)
* samling [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->