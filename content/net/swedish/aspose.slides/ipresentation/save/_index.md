---
title: Save
second_title: Aspose.Sildes för .NET API-referens
description: Sparar alla bilder i en presentation till en fil med det angivna formatet.
type: docs
weight: 380
url: /sv/aspose.slides/ipresentation/save/
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
* gränssnitt [IPresentation](../../ipresentation)
* namnrymd [Aspose.Slides](../../ipresentation)
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
* gränssnitt [IPresentation](../../ipresentation)
* namnrymd [Aspose.Slides](../../ipresentation)
* samling [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Sparar alla bilder i en presentation till en fil med det angivna formatet och med ytterligare alternativ.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* gränssnitt [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* gränssnitt [IPresentation](../../ipresentation)
* namnrymd [Aspose.Slides](../../ipresentation)
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

| Undantag | Villkor |
| --- | --- |
| NotSupportedException | Om du försöker spara en krypterad fil i något format som inte är Office 2007-2010 |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* gränssnitt [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* gränssnitt [IPresentation](../../ipresentation)
* namnrymd [Aspose.Slides](../../ipresentation)
* samling [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Sparar angivna bilder i en presentation till en fil med det angivna formatet.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array med bildpositioner, med början från 1. |
| format | SaveFormat | Format of the exported data. |

### Undantag

| Undantag | Villkor |
| --- | --- |
| ArgumentNullException | När stream- eller slides-parameter är null. |
| ArgumentOutOfRangeException | När slides-parameter innehåller fel sidnummer. |
| InvalidOperationException | När ett icke-stödd SaveFormat används, t.ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* gränssnitt [IPresentation](../../ipresentation)
* namnrymd [Aspose.Slides](../../ipresentation)
* samling [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Sparar angivna bilder i en presentation till en fil med det angivna formatet.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array med bildpositioner, med början från 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Undantag

| Undantag | Villkor |
| --- | --- |
| ArgumentNullException | När stream- eller slides-parameter är null. |
| ArgumentOutOfRangeException | När slides-parameter innehåller fel sidnummer. |
| InvalidOperationException | När ett icke-stödd SaveFormat används, t.ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* gränssnitt [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* gränssnitt [IPresentation](../../ipresentation)
* namnrymd [Aspose.Slides](../../ipresentation)
* samling [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Sparar angivna bilder i en presentation till en ström i det angivna formatet.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array med bildpositioner, med början från 1. |
| format | SaveFormat | Format of the exported data. |

### Undantag

| Undantag | Villkor |
| --- | --- |
| ArgumentNullException | När stream- eller slides-parameter är null. |
| ArgumentOutOfRangeException | När slides-parameter innehåller fel sidnummer. |
| InvalidOperationException | När ett icke-stödd SaveFormat används, t.ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* gränssnitt [IPresentation](../../ipresentation)
* namnrymd [Aspose.Slides](../../ipresentation)
* samling [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Sparar angivna bilder i en presentation till en ström i det angivna formatet.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array med bildpositioner, med början från 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Undantag

| Undantag | Villkor |
| --- | --- |
| ArgumentNullException | När stream- eller slides-parameter är null. |
| ArgumentOutOfRangeException | När slides-parameter innehåller fel sidnummer. |
| InvalidOperationException | När ett icke-stödd SaveFormat används, t.ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* gränssnitt [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* gränssnitt [IPresentation](../../ipresentation)
* namnrymd [Aspose.Slides](../../ipresentation)
* samling [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Sparar alla bilder i en presentation till en uppsättning filer som representerar XAML-markup.

```csharp
public void Save(IXamlOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | IXamlOptions | XAML-formatalternativen. |

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
* gränssnitt [IPresentation](../../ipresentation)
* namnrymd [Aspose.Slides](../../ipresentation)
* samling [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->