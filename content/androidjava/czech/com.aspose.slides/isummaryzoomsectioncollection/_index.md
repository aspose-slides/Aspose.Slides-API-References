---
title: ISummaryZoomSectionCollection
second_title: Aspose.Slides pro Android přes Java API Reference
description: Representuje kolekci objektů Summary Zoom Section.
type: docs
url: /cs/com.aspose.slides/isummaryzoomsectioncollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface ISummaryZoomSectionCollection extends IGenericCollection<ISummaryZoomSection>
```

Representuje kolekci objektů Summary Zoom Section.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | Vytvoří nový objekt Summary Zoom Section a přidá jej do kolekce |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | Vrátí prvek Summary Zoom Section pro danou sekci. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | Odstraní objekt Summary Zoom Section z kolekce. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | Vrátí index zadaného objektu SummaryZoomSection. |
| [clear()](#clear--) | Odstraní všechny objekty SummaryZoomSection z kolekce. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISummaryZoomSection get_Item(int index)
```

Získá prvek na zadaném indexu. Pouze pro čtení [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

--------------------

> ```
> Příklad ukazuje získání prvku Summary Zoom Section podle indexu:
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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection addSummaryZoomSection(ISection section)
```

Vytvoří nový objekt Summary Zoom Section a přidá jej do kolekce

--------------------

> ```
> Příklad ukazuje získání prvku Summary Zoom Section podle indexu:
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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekce pro nový prvek Summary Zoom Section [ISection](../../com.aspose.slides/isection)

--------------------

Pokud již v kolekci existuje prvek pro tuto sekci, vrátí se existující prvek.|

**Návratová hodnota:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - Přidáno [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) prvek
### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection getSummarySection(ISection section)
```

Vrátí prvek Summary Zoom Section pro danou sekci.

--------------------

> ```
> Příklad ukazuje získání prvku Summary Zoom Section podle indexu:
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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekce k nalezení [ISection](../../com.aspose.slides/isection) |

**Návratová hodnota:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) nebo null, pokud kolekce neobsahuje prvek pro sekci.
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract void removeSummaryZoomSection(ISection section)
```

Odstraní objekt Summary Zoom Section z kolekce.

--------------------

> ```
> Příklad ukazuje získání prvku Summary Zoom Section podle indexu:
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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekce, pro kterou se má odstranit prvek Summary Zoom Section [ISection](../../com.aspose.slides/isection). |

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public abstract int indexOf(ISummaryZoomSection summaryZoomSection)
```

Vrátí index zadaného objektu SummaryZoomSection.

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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | Objekt SummaryZoomSection k nalezení [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**Návratová hodnota:**
int - Index objektu SummaryZoomSection nebo -1, pokud objekt SummaryZoomSection není součástí této kolekce.
### clear() {#clear--}
```
public abstract void clear()
```

Odstraní všechny objekty SummaryZoomSection z kolekce.

--------------------

> ```
> Příklad ukazuje získání prvku Summary Zoom Section podle indexu:
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
