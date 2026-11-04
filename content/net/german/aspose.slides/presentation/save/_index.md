---
title: Save
second_title: Aspose.Sildes für .NET API-Referenz
description: Speichert alle Folien einer Präsentation in einer Datei mit dem angegebenen Format.
type: docs
weight: 400
url: /de/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

Speichert alle Folien einer Präsentation in einer Datei mit dem angegebenen Format.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | SaveFormat | Format of the exported data. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* Klasse [Presentation](../../presentation)
* Namensraum [Aspose.Slides](../../presentation)
* Assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Speichert alle Folien einer Präsentation in einem Stream im angegebenen Format.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* Klasse [Presentation](../../presentation)
* Namensraum [Aspose.Slides](../../presentation)
* Assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* Schnittstelle [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* Klasse [Presentation](../../presentation)
* Namensraum [Aspose.Slides](../../presentation)
* Assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Speichert alle Folien einer Präsentation in einem Stream im angegebenen Format und mit zusätzlichen Optionen.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| NotSupportedException | Wenn Sie versuchen, eine verschlüsselte Datei in keinem Office 2007-2010-Format zu speichern |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* Schnittstelle [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* Klasse [Presentation](../../presentation)
* Namensraum [Aspose.Slides](../../presentation)
* Assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Speichert alle Folien einer Präsentation in einer Menge von Dateien, die XAML-Markup darstellen.

```csharp
public void Save(IXamlOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | IXamlOptions | Die XAML-Formatoptionen. |

### Beispiele

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Siehe auch

* Schnittstelle [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* Klasse [Presentation](../../presentation)
* Namensraum [Aspose.Slides](../../presentation)
* Assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Speichert angegebene Folien einer Präsentation in einer Datei mit dem angegebenen Format unter Beibehaltung der Seitennummern.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array mit Folienpositionen, beginnend bei 1. |
| format | SaveFormat | Format of the exported data. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wenn der stream- oder slides-Parameter null ist. |
| ArgumentOutOfRangeException | Wenn der slides-Parameter falsche Seitennummern enthält. |
| InvalidOperationException | Wenn ein nicht unterstütztes SaveFormat verwendet wird, z. B. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* Klasse [Presentation](../../presentation)
* Namensraum [Aspose.Slides](../../presentation)
* Assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Speichert angegebene Folien einer Präsentation in einer Datei mit dem angegebenen Format unter Beibehaltung der Seitennummern.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array mit Folienpositionen, beginnend bei 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* Schnittstelle [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* Klasse [Presentation](../../presentation)
* Namensraum [Aspose.Slides](../../presentation)
* Assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Speichert angegebene Folien einer Präsentation in einem Stream im angegebenen Format unter Beibehaltung der Seitennummern.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array mit Folienpositionen, beginnend bei 1. |
| format | SaveFormat | Format of the exported data. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* Klasse [Presentation](../../presentation)
* Namensraum [Aspose.Slides](../../presentation)
* Assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Speichert angegebene Folien einer Präsentation in einem Stream im angegebenen Format unter Beibehaltung der Seitennummern.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array mit Folienpositionen, beginnend bei 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wenn der stream- oder slides-Parameter null ist. |
| ArgumentOutOfRangeException | Wenn der slides-Parameter falsche Seitennummern enthält. |
| InvalidOperationException | Wenn ein nicht unterstütztes SaveFormat verwendet wird, z. B. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Beispiele

Das folgende Beispiel zeigt, wie man PowerPoint nach PNG konvertiert.

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

Das folgende Beispiel zeigt, wie man PowerPoint nach PNG mit benutzerdefinierten Abmessungen konvertiert.

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

Das folgende Beispiel zeigt, wie man PowerPoint nach PNG mit benutzerdefinierter Größe konvertiert.

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

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* Schnittstelle [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* Klasse [Presentation](../../presentation)
* Namensraum [Aspose.Slides](../../presentation)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->