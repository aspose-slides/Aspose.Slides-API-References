---
title: ToSvg
second_title: Aspose.Slides für .NET-API-Referenz
description: konvertiertPresentationaspose.slides/presentation zu SVG.
type: docs
weight: 30
url: /de/net/aspose.slides.lowcode/convert/tosvg/
---
## ToSvg(string) {#tosvg_3}

konvertiert[`Presentation`](../../../aspose.slides/presentation) zu SVG.

```csharp
public static void ToSvg(string presPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| presPath | String | Pfad der Eingabepräsentation |

### Beispiele

```csharp
Convert.ToSvg("pres.pptx");
```

### Siehe auch

* class [Convert](../../convert)
* namensraum [Aspose.Slides.LowCode](../../convert)
* Montage [Aspose.Slides](../../../)

---

## ToSvg(string, GetOutPathCallback) {#tosvg_4}

konvertiert[`Presentation`](../../../aspose.slides/presentation) zu SVG.

```csharp
public static void ToSvg(string presPath, GetOutPathCallback getOutPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| presPath | String | Pfad der Eingabepräsentation |
| getOutPath | GetOutPathCallback | Rückruf, der den SVG-Ausgabepfad für jede Folie in der Präsentation zurückgibt |

### Beispiele

```csharp
Convert.ToSvg("pres.pptx", (slide, index) => $"pres_{index}-out.svg");
```

### Siehe auch

* delegate [GetOutPathCallback](../../convert.getoutpathcallback)
* class [Convert](../../convert)
* namensraum [Aspose.Slides.LowCode](../../convert)
* Montage [Aspose.Slides](../../../)

---

## ToSvg(Presentation, GetOutPathCallback) {#tosvg_1}

konvertiert[`Presentation`](../../../aspose.slides/presentation) zu SVG.

```csharp
public static void ToSvg(Presentation pres, GetOutPathCallback getOutPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | Presentation | Input-Präsentation |
| getOutPath | GetOutPathCallback | &gt;Callback, der den SVG-Ausgabepfad für jede Folie in der Präsentation zurückgibt |

### Beispiele

```csharp
using (Presentation pres = new Presentation("input.pptx"))    
{
    Convert.ToSvg(pres, (slide, index) => $"pres_{index}-out.svg");
} 
```

### Siehe auch

* class [Presentation](../../../aspose.slides/presentation)
* delegate [GetOutPathCallback](../../convert.getoutpathcallback)
* class [Convert](../../convert)
* namensraum [Aspose.Slides.LowCode](../../convert)
* Montage [Aspose.Slides](../../../)

---

## ToSvg(Presentation, ISVGOptions) {#tosvg}

konvertiert[`Presentation`](../../../aspose.slides/presentation) zu SVG.

```csharp
public static void ToSvg(Presentation pres, ISVGOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | Presentation | Input-Präsentation |
| options | ISVGOptions | SVG-Exportoptionen |

### Beispiele

```csharp
using (Presentation pres = new Presentation("input.pptx"))    
{
    Convert.ToSvg(pres, new SVGOptions { VectorizeText = true });
}  
```

### Siehe auch

* class [Presentation](../../../aspose.slides/presentation)
* interface [ISVGOptions](../../../aspose.slides.export/isvgoptions)
* class [Convert](../../convert)
* namensraum [Aspose.Slides.LowCode](../../convert)
* Montage [Aspose.Slides](../../../)

---

## ToSvg(Presentation, GetOutPathCallback, ISVGOptions) {#tosvg_2}

konvertiert[`Presentation`](../../../aspose.slides/presentation) zu SVG.

```csharp
public static void ToSvg(Presentation pres, GetOutPathCallback getOutPath, ISVGOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | Presentation | Input-Präsentation |
| getOutPath | GetOutPathCallback | Rückruf, der den SVG-Ausgabepfad für jede Folie in der Präsentation zurückgibt |
| options | ISVGOptions | SVG-Exportoptionen |

### Beispiele

```csharp
using (Presentation pres = new Presentation("input.pptx"))    
{
    Convert.ToSvg(pres, (slide, index) => $"pres_{index}-out.svg", new SVGOptions { VectorizeText = true });
} 
```

### Siehe auch

* class [Presentation](../../../aspose.slides/presentation)
* delegate [GetOutPathCallback](../../convert.getoutpathcallback)
* interface [ISVGOptions](../../../aspose.slides.export/isvgoptions)
* class [Convert](../../convert)
* namensraum [Aspose.Slides.LowCode](../../convert)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->