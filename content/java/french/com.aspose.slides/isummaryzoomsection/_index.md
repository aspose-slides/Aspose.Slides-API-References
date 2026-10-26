---
title: ISummaryZoomSection
second_title: Référence de l'API Aspose.Slides pour Java
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
| [getTitle()](#getTitle--) | Retourne le texte du titre de l'objet Summary Zoom Section. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Retourne le texte du titre de l'objet Summary Zoom Section. |
| [getDescription()](#getDescription--) | Retourne le texte de la description de l'objet Summary Zoom Section. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Retourne le texte de la description de l'objet Summary Zoom Section. |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```


Retourne le texte du titre de l'objet Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```

**Valeur retournée :**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```


Retourne le texte du titre de l'objet Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


Retourne le texte de la description de l'objet Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
>  ```

**Valeur retournée :**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public abstract void setDescription(String value)
```


Retourne le texte de la description de l'objet Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |