---
title: Save
second_title: Aspose.Sildes för .NET API-referens
description: Sparar alla bilder i en presentation till en fil med det angivna formatet.
type: docs
weight: 390
url: /sv/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

Sparar alla bilder i en presentation till en fil med det angivna formatet.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | String | Sökväg till den skapade filen. |
| format | SaveFormat | Format för den exporterade datan. |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Sparar alla bilder i en presentation till en ström i det angivna formatet.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Utdatastream. |
| format | SaveFormat | Format för den exporterade datan. |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Sparar alla bilder i en presentation till en fil med det angivna formatet och med ytterligare alternativ.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | String | Sökväg till den skapade filen. |
| format | SaveFormat | Format för den exporterade datan. |
| options | ISaveOptions | Ytterligare formatalternativ. |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Sparar alla bilder i en presentation till en ström i det angivna formatet och med ytterligare alternativ.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Utdatastream. |
| format | SaveFormat | Format för den exporterade datan. |
| options | ISaveOptions | Ytterligare formatalternativ. |

### Undantag

| undantag | villkor |
| --- | --- |
| NotSupportedException | Om du försöker spara en krypterad fil i något format som inte är Office 2007-2010 |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Sparar specificerade bilder i en presentation till en fil med det angivna formatet.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | String | Sökväg till den skapade filen. |
| slides | Int32[] | Array med bildpositioner, med början på 1. |
| format | SaveFormat | Format för den exporterade datan. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | När stream- eller slides-parametern är null. |
| ArgumentOutOfRangeException | När slides-parametern innehåller fel sidnummer. |
| InvalidOperationException | När ett ej stödd SaveFormat används, t.ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Sparar specificerade bilder i en presentation till en fil med det angivna formatet.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | String | Sökväg till den skapade filen. |
| slides | Int32[] | Array med bildpositioner, med början på 1. |
| format | SaveFormat | Format för den exporterade datan. |
| options | ISaveOptions | Ytterligare formatalternativ. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | När stream- eller slides-parametern är null. |
| ArgumentOutOfRangeException | När slides-parametern innehåller fel sidnummer. |
| InvalidOperationException | När ett ej stödd SaveFormat används, t.ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Sparar specificerade bilder i en presentation till en ström i det angivna formatet.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Utdatastream. |
| slides | Int32[] | Array med bildpositioner, med början på 1. |
| format | SaveFormat | Format för den exporterade datan. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | När stream- eller slides-parametern är null. |
| ArgumentOutOfRangeException | När slides-parametern innehåller fel sidnummer. |
| InvalidOperationException | När ett ej stödd SaveFormat används, t.ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Sparar specificerade bilder i en presentation till en ström i det angivna formatet och med ytterligare alternativ.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Utdatastream. |
| slides | Int32[] | Array med bildpositioner, med början på 1. |
| format | SaveFormat | Format för den exporterade datan. |
| options | ISaveOptions | Ytterligare formatalternativ. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | När stream- eller slides-parametern är null. |
| ArgumentOutOfRangeException | När slides-parametern innehåller fel sidnummer. |
| InvalidOperationException | När ett ej stödd SaveFormat används, t.ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Se även

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Sparar alla bilder i en presentation till ett set med filer som representerar XAML-markup.

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

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->