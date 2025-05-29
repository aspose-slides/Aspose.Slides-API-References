---
title: AddClone
second_title: Aspose.Slides für .NET API Referenz
description: Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu.
type: docs
weight: 20
url: /de/aspose.slides/islidecollection/addclone/
---

## AddClone(ISlide) {#addclone}

Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu.

```csharp
public ISlide AddClone(ISlide sourceSlide)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceSlide | ISlide | Folie zum Klonen. |

### Rückgabewert

Neue Folie.

### Bemerkungen

Beim Klonen einer Folie zwischen verschiedenen Präsentationen kann auch die Masterfolie geklont werden. Ein internes Register wird verwendet, um automatisch geklonte Masterfolien zu verfolgen, um die Erstellung mehrerer Klone derselben Masterfolie zu verhindern. Das manuelle Klonen von Masterfolien wird weder verhindert noch registriert. Wenn Sie mehr Kontrolle über den Klonprozess benötigen, verwenden Sie [`AddClone`](../addclone) oder [`AddClone`](../addclone) zum Klonen von Folien, [`AddClone`](../../igloballayoutslidecollection/addclone) oder [`AddClone`](../../igloballayoutslidecollection/addclone) zum Klonen von Layouts und [`AddClone`](../../imasterslidecollection/addclone) zum Klonen von Masterfolien.

### Siehe Auch

* Schnittstelle [ISlide](../../islide)
* Schnittstelle [ISlideCollection](../../islidecollection)
* Namensraum [Aspose.Slides](../../islidecollection)
* Assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, ISection) {#addclone_3}

Fügt eine Kopie einer angegebenen Folie am Ende der angegebenen Sektion hinzu.

```csharp
public ISlide AddClone(ISlide sourceSlide, ISection section)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceSlide | ISlide | Folie zum Klonen. |
| section | ISection | Sektion für eine neue Folie. |

### Rückgabewert

Neue Folie.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException |  |
| [PptxEditException](../../pptxeditexception) |  |

### Beispiele

```csharp
[C#]
using (IPresentation presentation = new Presentation())
{
    presentation.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
    presentation.Sections.AddSection("Abschnitt 1", presentation.Slides[0]);
    
    ISection section2 = presentation.Sections.AppendEmptySection("Abschnitt 2");
    presentation.Slides.AddClone(presentation.Slides[0], section2);
    
    // Jetzt enthält der zweite Abschnitt eine Kopie der ersten Folie.
}
```

### Siehe Auch

* Schnittstelle [ISlide](../../islide)
* Schnittstelle [ISection](../../isection)
* Schnittstelle [ISlideCollection](../../islidecollection)
* Namensraum [Aspose.Slides](../../islidecollection)
* Assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, ILayoutSlide) {#addclone_1}

Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu.

```csharp
public ISlide AddClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceSlide | ISlide | Folie zum Klonen. |
| destLayout | ILayoutSlide | Layoutfolie für eine neue Folie. |

### Rückgabewert

Neue Folie.

### Siehe Auch

* Schnittstelle [ISlide](../../islide)
* Schnittstelle [ILayoutSlide](../../ilayoutslide)
* Schnittstelle [ISlideCollection](../../islidecollection)
* Namensraum [Aspose.Slides](../../islidecollection)
* Assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, IMasterSlide, bool) {#addclone_2}

Fügt eine Kopie einer angegebenen Quellfolie am Ende der Sammlung hinzu. Das geeignete Layout wird automatisch aus der angegebenen Masterfolie ausgewählt (das geeignete Layout ist das Layout mit dem gleichen Typ oder Namen wie das Layout der Quellfolie). Wenn es kein geeignetes Layout gibt, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder eine PptxEditException wird ausgelöst (wenn allowCloneMissingLayout false ist).

```csharp
public ISlide AddClone(ISlide sourceSlide, IMasterSlide destMaster, bool allowCloneMissingLayout)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceSlide | ISlide | Folie zum Klonen. |
| destMaster | IMasterSlide | Masterfolie für eine neue Folie. |
| allowCloneMissingLayout | Boolean | Wenn es kein geeignetes Layout in der angegebenen Masterfolie gibt, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder eine PptxEditException wird ausgelöst (wenn allowCloneMissingLayout false ist). |

### Rückgabewert

Neue Folie.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Wird ausgelöst, wenn es kein geeignetes Layout in der angegebenen Masterfolie gibt und allowCloneMissingLayout false ist. |

### Siehe Auch

* Schnittstelle [ISlide](../../islide)
* Schnittstelle [IMasterSlide](../../imasterslide)
* Schnittstelle [ISlideCollection](../../islidecollection)
* Namensraum [Aspose.Slides](../../islidecollection)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->