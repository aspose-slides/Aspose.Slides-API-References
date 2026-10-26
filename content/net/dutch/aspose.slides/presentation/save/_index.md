---
title: Save
second_title: Aspose.Sildes voor .NET API-referentie
description: Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat.
type: docs
weight: 390
url: /nl/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | String | Pad naar het aangemaakte bestand. |
| format | SaveFormat | Formaat van de geëxporteerde gegevens. |

### Zie ook

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Slaat alle dia's van een presentatie op in een stream met het opgegeven formaat.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | Uitvoerstroom. |
| format | SaveFormat | Formaat van de geëxporteerde gegevens. |

### Zie ook

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### Zie ook

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Slaat alle dia's van een presentatie op in een stream met het opgegeven formaat en met extra opties.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | Uitvoerstroom. |
| format | SaveFormat | Formaat van de geëxporteerde gegevens. |
| options | ISaveOptions | Extra formaatopties. |

### Excepties

| exceptie | conditie |
| --- | --- |
| NotSupportedException | Als u probeert een versleuteld bestand op te slaan in een niet-Office 2007-2010 formaat |

### Zie ook

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Slaat alle dia's van een presentatie op in een set bestanden die XAML-markup weergeven.

```csharp
public void Save(IXamlOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | IXamlOptions | De XAML-formatopties. |

### Voorbeelden

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Zie ook

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat, met behoud van paginanummers.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | String | Pad naar het aangemaakte bestand. |
| slides | Int32[] | Array met dia-posities, beginnend bij 1. |
| format | SaveFormat | Formaat van de geëxporteerde gegevens. |

### Excepties

| exceptie | conditie |
| --- | --- |
| ArgumentNullException | Wanneer de stream- of slides-parameter null is. |
| ArgumentOutOfRangeException | Wanneer de slides-parameter onjuiste paginanummers bevat. |
| InvalidOperationException | Wanneer een niet-ondersteund SaveFormat wordt gebruikt, bijv. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Zie ook

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat, met behoud van paginanummers en extra opties.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | String | Pad naar het aangemaakte bestand. |
| slides | Int32[] | Array met dia-posities, beginnend bij 1. |
| format | SaveFormat | Formaat van de geëxporteerde gegevens. |
| options | ISaveOptions | Extra formaatopties. |

### Zie ook

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Slaat opgegeven dia's van een presentatie op in een stream met het opgegeven formaat, met behoud van paginanummers.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | Uitvoerstroom. |
| slides | Int32[] | Array met dia-posities, beginnend bij 1. |
| format | SaveFormat | Formaat van de geëxporteerde gegevens. |

### Zie ook

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Slaat opgegeven dia's van een presentatie op in een stream met het opgegeven formaat, met behoud van paginanummers en extra opties.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | Uitvoerstroom. |
| slides | Int32[] | Array met dia-posities, beginnend bij 1. |
| format | SaveFormat | Formaat van de geëxporteerde gegevens. |
| options | ISaveOptions | Extra formaatopties. |

### Excepties

| exceptie | conditie |
| --- | --- |
| ArgumentNullException | Wanneer de stream- of slides-parameter null is. |
| ArgumentOutOfRangeException | Wanneer de slides-parameter onjuiste paginanummers bevat. |
| InvalidOperationException | Wanneer een niet-ondersteund SaveFormat wordt gebruikt, bijv. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Voorbeelden

Het volgende voorbeeld toont hoe PowerPoint naar PNG kan worden geconverteerd.

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

Het volgende voorbeeld toont hoe PowerPoint naar PNG kan worden geconverteerd met aangepaste afmetingen.

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

Het volgende voorbeeld toont hoe PowerPoint naar PNG kan worden geconverteerd met een aangepaste grootte.

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

### Zie ook

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->