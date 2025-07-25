---
title: AddClone
second_title: Aspose.Sildes für .NET API Referenz
description: Fügt eine Kopie einer angegebenen Layout-Folie der Präsentation hinzu.
type: docs
weight: 20
url: /de/aspose.slides/globallayoutslidecollection/addclone/
---

## AddClone(ILayoutSlide) {#addclone}

Fügt eine Kopie einer angegebenen Layout-Folie der Präsentation hinzu.

```csharp
public ILayoutSlide AddClone(ILayoutSlide sourceLayout)
```

| Parameter     | Typ         | Beschreibung              |
|---------------|-------------|---------------------------|
| sourceLayout  | ILayoutSlide| Folie zum Klonen.        |

### Rückgabewert

Hinzugefügte Folie.

### Anmerkungen

Beim Klonen eines Layouts zwischen verschiedenen Präsentationen kann auch das Masterlayout geklont werden, um die Quellformatierung beizubehalten. Ein internes Register wird verwendet, um automatisch geklonte Masterfolien nachzuverfolgen, um die Erstellung mehrerer Klone derselben Masterfolie zu verhindern. Manuelles Klonen von Masterfolien wird weder verhindert noch registriert.

### Siehe auch

* Schnittstelle [ILayoutSlide](../../ilayoutslide)
* Klasse [GlobalLayoutSlideCollection](../../globallayoutslidecollection)
* Namespace [Aspose.Slides](../../globallayoutslidecollection)
* Assembly [Aspose.Slides](../../../)

---

## AddClone(ILayoutSlide, IMasterSlide) {#addclone_1}

Fügt eine Kopie einer angegebenen Layout-Folie der Präsentation hinzu.

```csharp
public ILayoutSlide AddClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

| Parameter     | Typ         | Beschreibung              |
|---------------|-------------|---------------------------|
| sourceLayout  | ILayoutSlide| Folie zum Klonen.        |
| destMaster    | IMasterSlide| Masterfolie für ein neues Layout. |

### Rückgabewert

Hinzugefügte Folie.

### Anmerkungen

1) Das neue Layout wird mit dem definierten Master in der Zielpräsentation verknüpft. Dies entspricht dem Kopieren/Einfügen mit der Option „Verwende Zielthema“ in PowerPoint. 2) Das Pendant zu dieser Methode ist die Methode [`AddClone`](../../imasterlayoutslidecollection/addclone), die über die Eigenschaft [`LayoutSlides`](../../imasterslide/layoutslides) aufgerufen werden kann.

### Siehe auch

* Schnittstelle [ILayoutSlide](../../ilayoutslide)
* Schnittstelle [IMasterSlide](../../imasterslide)
* Klasse [GlobalLayoutSlideCollection](../../globallayoutslidecollection)
* Namespace [Aspose.Slides](../../globallayoutslidecollection)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->