---
title: ISummaryZoomSectionCollection
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt eine Sammlung von Summary Zoom Section-Objekten dar.
type: docs
url: /de/com.aspose.slides/isummaryzoomsectioncollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface ISummaryZoomSectionCollection extends IGenericCollection<ISummaryZoomSection>
```

Stellt eine Sammlung von Summary Zoom Section-Objekten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Liefert das Element am angegebenen Index. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | Erstellt ein neues Summary Zoom Section-Objekt und fügt es der Sammlung hinzu |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | Gibt das Summary Zoom Section-Element für den angegebenen Abschnitt zurück. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | Entfernt das Summary Zoom Section-Objekt aus der Sammlung. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | Gibt den Index des angegebenen SummaryZoomSection-Objekts zurück. |
| [clear()](#clear--) | Entfernt alle SummaryZoomSection-Objekte aus der Sammlung. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISummaryZoomSection get_Item(int index)
```

Liefert das Element am angegebenen Index. Schreibgeschützt [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection zoomSection = collection.get_Item(1);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection addSummaryZoomSection(ISection section)
```

Erstellt ein neues Summary Zoom Section-Objekt und fügt es der Sammlung hinzu

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection newZoomSection = collection.addSummaryZoomSection(pres.getSections().get_Item(3));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Abschnitt für ein neues Summary Zoom Section-Element [ISection](../../com.aspose.slides/isection)

Falls bereits ein Element für diesen Abschnitt in der Sammlung existiert, wird das bestehende Element zurückgegeben.

**Rückgabewert:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - Hinzugefügtes [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)-Element
### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection getSummarySection(ISection section)
```

Gibt das Summary Zoom Section-Element für den angegebenen Abschnitt zurück.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Abschnitt zu finden [ISection](../../com.aspose.slides/isection) |

**Rückgabewert:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) oder null, wenn die Sammlung kein Element für den Abschnitt enthält.
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract void removeSummaryZoomSection(ISection section)
```

Entfernt das Summary Zoom Section-Objekt aus der Sammlung.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.removeSummaryZoomSection(pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Abschnitt, für den das Summary Zoom Section-Element entfernt werden soll [ISection](../../com.aspose.slides/isection). |

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public abstract int indexOf(ISummaryZoomSection summaryZoomSection)
```

Gibt den Index des angegebenen SummaryZoomSection-Objekts zurück.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>       int idx = collection.indexOf(selectedObject);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | SummaryZoomSection-Objekt, das gefunden werden soll [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**Rückgabewert:**
int - Index eines SummaryZoomSection-Objekts oder -1, wenn das SummaryZoomSection-Objekt nicht zu dieser Sammlung gehört.
### clear() {#clear--}
```
public abstract void clear()
```

Entfernt alle SummaryZoomSection-Objekte aus der Sammlung.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.clear();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
