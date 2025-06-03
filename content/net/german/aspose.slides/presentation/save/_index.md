---
title: Save
second_title: Aspose.Slides für .NET API-Referenz
description: Speichert bestimmte Folien einer Präsentation in einer Datei im angegebenen Format unter Beibehaltung der Seitenzahl.
type: docs
weight: 380
url: /de/aspose.slides/presentation/save/
---

## Save(string, int[], SaveFormat) {#save_7}

Speichert bestimmte Folien einer Präsentation in einer Datei im angegebenen Format unter Beibehaltung der Seitenzahl.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | String | Pfad zur erstellten Datei. |
| slides | Int32[] | Array mit Folienpositionen, beginnend bei 1. |
| format | SaveFormat | Format der exportierten Daten. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wenn der Stream oder der slides-Parameter null ist. |
| ArgumentOutOfRangeException | Wenn der slides-Parameter falsche Seitenzahlen enthält. |
| InvalidOperationException | Wenn ein nicht unterstütztes SaveFormat verwendet wird, z.B. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Speichert bestimmte Folien einer Präsentation in einer Datei im angegebenen Format unter Beibehaltung der Seitenzahl.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | String | Pfad zur erstellten Datei. |
| slides | Int32[] | Array mit Folienpositionen, beginnend bei 1. |
| format | SaveFormat | Format der exportierten Daten. |
| options | ISaveOptions | Zusätzliche Formatoptionen. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Speichert bestimmte Folien einer Präsentation in einem Stream im angegebenen Format unter Beibehaltung der Seitenzahl.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ausgabestream. |
| slides | Int32[] | Array mit Folienpositionen, beginnend bei 1. |
| format | SaveFormat | Format der exportierten Daten. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Speichert bestimmte Folien einer Präsentation in einem Stream im angegebenen Format unter Beibehaltung der Seitenzahl.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ausgabestream. |
| slides | Int32[] | Array mit Folienpositionen, beginnend bei 1. |
| format | SaveFormat | Format der exportierten Daten. |
| options | ISaveOptions | Zusätzliche Formatoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wenn der Stream oder der slides-Parameter null ist. |
| ArgumentOutOfRangeException | Wenn der slides-Parameter falsche Seitenzahlen enthält. |
| InvalidOperationException | Wenn ein nicht unterstütztes SaveFormat verwendet wird, z.B. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Beispiele

Das folgende Beispiel zeigt, wie man PowerPoint in PNG konvertiert.

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

Das folgende Beispiel zeigt, wie man PowerPoint in PNG mit benutzerdefinierten Dimensionen konvertiert.

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

Das folgende Beispiel zeigt, wie man PowerPoint in PNG mit benutzerdefinierter Größe konvertiert.

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

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat) {#save_5}

Speichert alle Folien einer Präsentation in einer Datei im angegebenen Format.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | String | Pfad zur erstellten Datei. |
| format | SaveFormat | Format der exportierten Daten. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Speichert alle Folien einer Präsentation in einem Stream im angegebenen Format.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ausgabestream. |
| format | SaveFormat | Format der exportierten Daten. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Speichert alle Folien einer Präsentation in einem Stream im angegebenen Format und mit zusätzlichen Optionen.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ausgabestream. |
| format | SaveFormat | Format der exportierten Daten. |
| options | ISaveOptions | Zusätzliche Formatoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| NotSupportedException | Wenn Sie versuchen, eine verschlüsselte Datei im nicht Office 2007-2010-Format zu speichern. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Speichert alle Folien einer Präsentation in einer Reihe von Dateien, die XAML-Markup darstellen.

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

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->