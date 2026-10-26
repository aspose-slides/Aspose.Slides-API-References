---
title: ISummaryZoomSectionCollection
second_title: Aspose.Slides Java API hivatkozás
description: A Summary Zoom Section objektumok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/isummaryzoomsectioncollection/
---
**Az összes megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ISummaryZoomSectionCollection extends IGenericCollection<ISummaryZoomSection>
```

A Summary Zoom Section objektumok gyűjteményét képviseli.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekéri az elemet a megadott indexnél. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | Új Summary Zoom Section objektumot hoz létre, és hozzáadja a gyűjteményhez |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | Visszaadja a Summary Zoom Section elemet a megadott szekcióhoz. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | Eltávolítja a Summary Zoom Section objektumot a gyűjteményből. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | Visszaad egy indexet a megadott SummaryZoomSection objektumhoz. |
| [clear()](#clear--) | Eltávolítja az összes SummaryZoomSection objektumot a gyűjteményből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISummaryZoomSection get_Item(int index)
```


Lekéri az elemet a megadott indexnél. Csak olvasható [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

--------------------

> ```
> A példa bemutatja, hogyan lehet a Summary Zoom Section elemet index alapján lekérni:
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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection addSummaryZoomSection(ISection section)
```


Új Summary Zoom Section objektumot hoz létre, és hozzáadja a gyűjteményhez

--------------------

> ```
> A példa bemutatja, hogyan lehet index alapján lekérni a Summary Zoom Section elemet:
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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Az új Summary Zoom Section elem szekciója [ISection](../../com.aspose.slides/isection)

Ha a szekcióhoz már létezik elem a gyűjteményben, akkor a meglévő elem kerül visszaadásra. |

**Visszatérési érték:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - Hozzáadott [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) elem
### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection getSummarySection(ISection section)
```


Visszaadja a Summary Zoom Section elemet a megadott szekcióhoz.

--------------------

> ```
> A példa bemutatja, hogyan lehet index alapján lekérni a Summary Zoom Section elemet:
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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | A keresett szekció [ISection](../../com.aspose.slides/isection) |

**Visszatérési érték:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) vagy null, ha a gyűjtemény nem tartalmaz elemet a szekcióhoz.
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract void removeSummaryZoomSection(ISection section)
```


Eltávolítja a Summary Zoom Section objektumot a gyűjteményből.

--------------------

> ```
> A példa bemutatja, hogyan lehet index alapján lekérni a Summary Zoom Section elemet:
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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Az a szekció, amelynek a Summary Zoom Section elemét el kell távolítani [ISection](../../com.aspose.slides/isection). |

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public abstract int indexOf(ISummaryZoomSection summaryZoomSection)
```


Visszaad egy indexet a megadott SummaryZoomSection objektumhoz.

--------------------

> ```
> A példa bemutatja, hogyan lehet index alapján lekérni a Summary Zoom Section elemet:
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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | A keresendő SummaryZoomSection objektum [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**Visszatérési érték:**
int - A SummaryZoomSection objektum indexe, vagy -1, ha a SummaryZoomSection objektum nem ebben a gyűjteményben van.
### clear() {#clear--}
```
public abstract void clear()
```


Eltávolítja az összes SummaryZoomSection objektumot a gyűjteményből.

--------------------

> ```
> A példa bemutatja, hogyan lehet index alapján lekérni a Summary Zoom Section elemet:
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
