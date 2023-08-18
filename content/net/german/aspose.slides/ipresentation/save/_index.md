---
title: Save
second_title: Aspose.Slides für .NET-API-Referenz
description: Speichert alle Folien einer Präsentation in eine Datei mit dem angegebenen Format.
type: docs
weight: 340
url: /de/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

Speichert alle Folien einer Präsentation in eine Datei mit dem angegebenen Format.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | String | Pfad zur erstellten Datei. |
| format | SaveFormat | Format der exportierten Daten. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namensraum [Aspose.Slides](../../ipresentation)
* Montage [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Speichert alle Folien einer Präsentation in einem Stream im angegebenen Format.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ausgabestrom. |
| format | SaveFormat | Format der exportierten Daten. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namensraum [Aspose.Slides](../../ipresentation)
* Montage [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Speichert alle Folien einer Präsentation in eine Datei mit dem angegebenen Format und mit zusätzlichen Optionen.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | String | Pfad zur erstellten Datei. |
| format | SaveFormat | Format der exportierten Daten. |
| options | ISaveOptions | Zusätzliche Formatoptionen. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namensraum [Aspose.Slides](../../ipresentation)
* Montage [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Speichert alle Folien einer Präsentation in einem Stream im angegebenen Format und mit zusätzlichen Optionen.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ausgabestrom. |
| format | SaveFormat | Format der exportierten Daten. |
| options | ISaveOptions | Zusätzliche Formatoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| NotSupportedException | Wenn Sie versuchen, eine verschlüsselte Datei im -Format zu speichern, kein Office 2007-2010-Format |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namensraum [Aspose.Slides](../../ipresentation)
* Montage [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_9}

Speichert bestimmte Folien einer Präsentation in einer Datei mit dem angegebenen Format.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | String | Pfad zur erstellten Datei. |
| slides | Int32[] | Array mit Objektträgerpositionen, beginnend bei 1. |
| format | SaveFormat | Format der exportierten Daten. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wenn der Stream- oder Folienparameter null ist. |
| ArgumentOutOfRangeException | Wenn der Folienparameter falsche Seitenzahlen enthält. |
| InvalidOperationException | Wenn ein nicht unterstütztes SaveFormat verwendet wird, z. B. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namensraum [Aspose.Slides](../../ipresentation)
* Montage [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_10}

Speichert bestimmte Folien einer Präsentation in einer Datei mit dem angegebenen Format.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | String | Pfad zur erstellten Datei. |
| slides | Int32[] | Array mit Objektträgerpositionen, beginnend bei 1. |
| format | SaveFormat | Format der exportierten Daten. |
| options | ISaveOptions | Zusätzliche Formatoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wenn der Stream- oder Folienparameter null ist. |
| ArgumentOutOfRangeException | Wenn der Folienparameter falsche Seitenzahlen enthält. |
| InvalidOperationException | Wenn ein nicht unterstütztes SaveFormat verwendet wird, z. B. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namensraum [Aspose.Slides](../../ipresentation)
* Montage [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Speichert bestimmte Folien einer Präsentation in einem Stream im angegebenen Format.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ausgabestrom. |
| slides | Int32[] | Array mit Objektträgerpositionen, beginnend bei 1. |
| format | SaveFormat | Format der exportierten Daten. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wenn der Stream- oder Folienparameter null ist. |
| ArgumentOutOfRangeException | Wenn der Folienparameter falsche Seitenzahlen enthält. |
| InvalidOperationException | Wenn ein nicht unterstütztes SaveFormat verwendet wird, z. B. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namensraum [Aspose.Slides](../../ipresentation)
* Montage [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Speichert bestimmte Folien einer Präsentation in einem Stream im angegebenen Format.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ausgabestrom. |
| slides | Int32[] | Array mit Objektträgerpositionen, beginnend bei 1. |
| format | SaveFormat | Format der exportierten Daten. |
| options | ISaveOptions | Zusätzliche Formatoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wenn der Stream- oder Folienparameter null ist. |
| ArgumentOutOfRangeException | Wenn der Folienparameter falsche Seitenzahlen enthält. |
| InvalidOperationException | Wenn ein nicht unterstütztes SaveFormat verwendet wird, z. B. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namensraum [Aspose.Slides](../../ipresentation)
* Montage [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Speichert alle Folien einer Präsentation in einem Satz von Dateien, die XAML-Markup darstellen.

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
* interface [IPresentation](../../ipresentation)
* namensraum [Aspose.Slides](../../ipresentation)
* Montage [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, HttpResponse, bool) {#save_8}

Sendet die Präsentation an den Client-Browser. Diese Methode fehlt in ClientProfile-Versionen von Aspose.Slide.

```csharp
public void Save(string fname, SaveFormat format, HttpResponse response, bool showInline)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | String | Der Name für die Präsentation, der im Clientbrowser angezeigt wird. Der Name sollte keinen Pfad enthalten. |
| format | SaveFormat | Format der exportierten Daten. |
| response | HttpResponse | Antwortobjekt, in dem das Dokument gespeichert werden soll. |
| showInline | Boolean | True, um eine Option zum Öffnen der Präsentation im Browser anzuzeigen. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namensraum [Aspose.Slides](../../ipresentation)
* Montage [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions, HttpResponse, bool) {#save_7}

Sendet die Präsentation an den Client-Browser. Diese Methode fehlt in ClientProfile-Versionen von Aspose.Slide.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options, HttpResponse response, 
    bool showInline)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | String | Der Name für die Präsentation, der im Clientbrowser angezeigt wird. Der Name sollte keinen Pfad enthalten. |
| format | SaveFormat | Format der exportierten Daten. |
| options | ISaveOptions | Zusätzliche Formatoptionen. |
| response | HttpResponse | Antwortobjekt, in dem das Dokument gespeichert werden soll. |
| showInline | Boolean | True, um eine Option zum Öffnen der Präsentation im Browser anzuzeigen. |

### Siehe auch

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namensraum [Aspose.Slides](../../ipresentation)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
