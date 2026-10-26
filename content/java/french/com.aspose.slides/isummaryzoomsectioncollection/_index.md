---
title: ISummaryZoomSectionCollection
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une collection d'objets Summary Zoom Section.
type: docs
url: /fr/com.aspose.slides/isummaryzoomsectioncollection/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCollection
```
public interface ISummaryZoomSectionCollection extends IGenericCollection<ISummaryZoomSection>
```

Représente une collection d'objets Summary Zoom Section.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | Crée un nouvel objet Summary Zoom Section et l'ajoute à la collection |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | Renvoie l'élément Summary Zoom Section pour la section donnée. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | Supprime l'objet Summary Zoom Section de la collection. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | Renvoie l'index de l'objet SummaryZoomSection spécifié. |
| [clear()](#clear--) | Supprime tous les objets SummaryZoomSection de la collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISummaryZoomSection get_Item(int index)
```


Obtient l'élément à l'index spécifié. Lecture seule [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

--------------------

> ```
> L'exemple montre comment obtenir un élément Summary Zoom Section par index:
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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection addSummaryZoomSection(ISection section)
```


Crée un nouvel objet Summary Zoom Section et l'ajoute à la collection

--------------------

> ```
> L'exemple montre comment obtenir un élément Summary Zoom Section par index:
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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Section pour un nouvel élément Summary Zoom Section [ISection](../../com.aspose.slides/isection)

Si un élément pour cette section existe déjà dans la collection, l'élément existant est retourné. |

**Renvoie :**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - Élément [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) ajouté
### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection getSummarySection(ISection section)
```


Renvoie l'élément Summary Zoom Section pour la section donnée.

--------------------

> ```
> L'exemple montre comment obtenir un élément Summary Zoom Section par index:
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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Section à rechercher [ISection](../../com.aspose.slides/isection) |

**Renvoie :**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) ou null si la collection ne contient pas d'élément pour la section.
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract void removeSummaryZoomSection(ISection section)
```


Supprime l'objet Summary Zoom Section de la collection.

--------------------

> ```
> L'exemple montre comment obtenir un élément Summary Zoom Section par index:
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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Section pour laquelle l'élément Summary Zoom Section doit être supprimé [ISection](../../com.aspose.slides/isection). |

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public abstract int indexOf(ISummaryZoomSection summaryZoomSection)
```


Renvoie l'index de l'objet SummaryZoomSection spécifié.

--------------------

> ```
> L'exemple montre comment obtenir un élément Summary Zoom Section par index:
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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | Objet SummaryZoomSection à trouver [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**Renvoie :**
int - Index d'un objet SummaryZoomSection ou -1 si l'objet SummaryZoomSection ne provient pas de cette collection.
### clear() {#clear--}
```
public abstract void clear()
```


Supprime tous les objets SummaryZoomSection de la collection.

--------------------

> ```
> L'exemple montre comment obtenir un élément Summary Zoom Section par index:
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
