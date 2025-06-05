---
title: InsertClone
second_title: Aspose.Sildes für .NET API Referenz
description: Fügt eine Kopie einer bestimmten Folie an einer bestimmten Position der Sammlung ein.
type: docs
weight: 120
url: /de/aspose.slides/slidecollection/insertclone/
---

## InsertClone(int, ISlide) {#insertclone}

Fügt eine Kopie einer bestimmten Folie an einer bestimmten Position der Sammlung ein.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Index der neuen Folie. |
| sourceSlide | ISlide | Folie, die geklont werden soll. |

### Rückgabewert

Eingefügte Folie.

### Hinweise

Beim Klonen einer Folie zwischen verschiedenen Präsentationen kann das Master der Folie ebenfalls geklont werden. Ein internes Register wird verwendet, um automatisch geklonte Masters zu verfolgen, um die Erstellung mehrerer Klone derselben Masterfolie zu verhindern. Manuelles Klonen von Masterfolien wird weder verhindert noch registriert. Wenn Sie mehr Kontrolle über den Klonprozess benötigen, verwenden Sie [`InsertClone`](../insertclone) oder [`InsertClone`](../insertclone) zum Klonen von Folien und [`AddClone`](../../imasterslidecollection/addclone) zum Klonen von Masters.

### Beispiele

Das folgende Beispiel zeigt, wie man an einer anderen Position innerhalb der Präsentation klont.

```csharp
[C#]
// Instanziieren der Presentation-Klasse, die eine Präsentationsdatei darstellt
using (Presentation pres = new Presentation("CloneWithInSamePresentation.pptx"))
{
    // Klone die gewünschte Folie ans Ende der Sammlung von Folien in derselben Präsentation
    ISlideCollection slds = pres.Slides;
    // Klone die gewünschte Folie an den angegebenen Index in derselben Präsentation
    slds.InsertClone(2, pres.Slides[1]);
    // Schreibe die modifizierte Präsentation auf die Festplatte
    pres.Save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
}
```

Das folgende Beispiel zeigt, wie man an einer anderen Position innerhalb der Präsentation klont.

```csharp
[C#]
// Instanziieren der Presentation-Klasse zum Laden der Quelldatei
using (Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx"))
{
    // Instanziieren der Presentation-Klasse für die Ziel-PPTX (wo die Folie geklont werden soll)
    using (Presentation destPres = new Presentation())
    {
        ISlideCollection slds = destPres.Slides;
        slds.InsertClone(2, srcPres.Slides[0]);
        // Schreibe die Zielpräsentation auf die Festplatte
        destPres.Save("Aspose2_out.pptx", SaveFormat.Pptx);
    }
}
```

### Siehe Auch

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, ILayoutSlide) {#insertclone_1}

Fügt eine Kopie einer bestimmten Folie an einer bestimmten Position der Sammlung ein.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Index der neuen Folie. |
| sourceSlide | ISlide | Folie, die geklont werden soll. |
| destLayout | ILayoutSlide | Layoutfolie für eine neue Folie. |

### Rückgabewert

Eingefügte Folie.

### Siehe Auch

* interface [ISlide](../../islide)
* interface [ILayoutSlide](../../ilayoutslide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, IMasterSlide, bool) {#insertclone_2}

Fügt eine Kopie einer bestimmten Quellfolie an einer bestimmten Position der Sammlung ein. Das geeignete Layout wird automatisch aus dem angegebenen Master ausgewählt (das geeignete Layout ist das Layout mit dem gleichen Typ oder Namen wie das Layout der Quellfolie). Wenn kein geeignetes Layout vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder eine PptxEditException wird ausgelöst (wenn allowCloneMissingLayout false ist).

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, 
    bool allowCloneMissingLayout)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Index der neuen Folie. |
| sourceSlide | ISlide | Folie, die geklont werden soll. |
| destMaster | IMasterSlide | Masterfolie für eine neue Folie. |
| allowCloneMissingLayout | Boolean | Wenn kein geeignetes Layout im angegebenen Master vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder eine PptxEditException wird ausgelöst (wenn allowCloneMissingLayout false ist). |

### Rückgabewert

Eingefügte Folie.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Wird ausgelöst, wenn im angegebenen Master kein geeignetes Layout vorhanden ist und allowCloneMissingLayout false ist. |

### Siehe Auch

* interface [ISlide](../../islide)
* interface [IMasterSlide](../../imasterslide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->