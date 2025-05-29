---
title: InsertClone
second_title: Aspose.Slides für .NET API-Referenz
description: Fügt eine Kopie einer bestimmten Folie an einer bestimmten Position der Sammlung ein.
type: docs
weight: 120
url: /de/aspose.slides/slidecollection/insertclone/
---

## InsertClone(int, ISlide) {#insertclone}

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

### Anmerkungen

Beim Klonen einer Folie zwischen verschiedenen Präsentationen kann auch das Master der Folie geklont werden. Ein internes Register wird verwendet, um automatisch geklonte Master zu verfolgen, um die Erstellung mehrerer Klone derselben Masterfolie zu verhindern. Manuelles Klonen von Masterfolien wird weder verhindert noch registriert. Wenn Sie mehr Kontrolle über den Klonprozess benötigen, verwenden Sie [`InsertClone`](../insertclone) oder [`InsertClone`](../insertclone) zum Klonen von Folien und [`AddClone`](../../imasterslidecollection/addclone) zum Klonen von Masterfolien.

### Beispiele

Das folgende Beispiel zeigt, wie man an einer anderen Position innerhalb der Präsentation klont.

```csharp
[C#]
// Instanziierung der Präsentationsklasse, die eine Präsentationsdatei darstellt
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
// Instanziierung der Präsentationsklasse zum Laden der Quelldatei der Präsentation
using (Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx"))
{
    // Instanziierung der Präsentationsklasse für die Ziel-PPTX (wo die Folie geklont werden soll)
    using (Presentation destPres = new Presentation())
    {
        ISlideCollection slds = destPres.Slides;
        slds.InsertClone(2, srcPres.Slides[0]);
        // Schreibe die Zielpräsentation auf die Festplatte
        destPres.Save("Aspose2_out.pptx", SaveFormat.Pptx);
    }
}
```

### Siehe auch

* Schnittstelle [ISlide](../../islide)
* Klasse [SlideCollection](../../slidecollection)
* Namensraum [Aspose.Slides](../../slidecollection)
* Assembly [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, ILayoutSlide) {#insertclone_1}

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

### Siehe auch

* Schnittstelle [ISlide](../../islide)
* Schnittstelle [ILayoutSlide](../../ilayoutslide)
* Klasse [SlideCollection](../../slidecollection)
* Namensraum [Aspose.Slides](../../slidecollection)
* Assembly [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, IMasterSlide, bool) {#insertclone_2}

Fügt eine Kopie einer bestimmten Quellfolie an einer bestimmten Position der Sammlung ein. Das geeignete Layout wird automatisch aus dem angegebenen Master ausgewählt (das geeignete Layout ist das Layout mit demselben Typ oder Namen wie das Layout der Quellfolie). Wenn kein geeignetes Layout vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder es wird eine PptxEditException ausgelöst (wenn allowCloneMissingLayout false ist).

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, 
    bool allowCloneMissingLayout)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Index der neuen Folie. |
| sourceSlide | ISlide | Folie, die geklont werden soll. |
| destMaster | IMasterSlide | Masterfolie für eine neue Folie. |
| allowCloneMissingLayout | Boolean | Wenn kein geeignetes Layout im angegebenen Master vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder es wird eine PptxEditException ausgelöst (wenn allowCloneMissingLayout false ist). |

### Rückgabewert

Eingefügte Folie.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Wird ausgelöst, wenn kein geeignetes Layout im angegebenen Master vorhanden ist und allowCloneMissingLayout false ist. |

### Siehe auch

* Schnittstelle [ISlide](../../islide)
* Schnittstelle [IMasterSlide](../../imasterslide)
* Klasse [SlideCollection](../../slidecollection)
* Namensraum [Aspose.Slides](../../slidecollection)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->