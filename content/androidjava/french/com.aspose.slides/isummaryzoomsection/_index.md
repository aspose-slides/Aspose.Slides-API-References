---
title: ISummaryZoomSection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un objet Summary Zoom Section dans un cadre Summary Zoom.
type: docs
url: /fr/com.aspose.slides/isummaryzoomsection/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

Représente un objet Summary Zoom Section dans un cadre Summary Zoom.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getTitle()](#getTitle--) | Renvoie le titre texte de l'objet Summary Zoom Section. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Renvoie le titre texte de l'objet Summary Zoom Section. |
| [getDescription()](#getDescription--) | Renvoie la description texte de l'objet Summary Zoom Section. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Renvoie la description texte de l'objet Summary Zoom Section. |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Renvoie le titre texte de l'objet Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Returns the text title of the Summary Zoom Section object.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

Returns the text description of the Summary Zoom Section object.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public abstract void setDescription(String value)

Renvoie la description texte de l'objet Summary Zoom Section.

--------------------

> ```
> Exemple :
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |