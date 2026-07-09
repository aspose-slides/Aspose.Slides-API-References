---
title: ISectionZoomFrame
second_title: "Référence de l'API Java Aspose.Slides pour Android"
description: "Représente un objet Section Zoom dans une diapositive."
type: docs
url: /fr/com.aspose.slides/isectionzoomframe/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

Représente un objet Section Zoom dans une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Obtient ou définit l'objet de section auquel l'objet Section Zoom est lié. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Obtient ou définit l'objet de section auquel l'objet Section Zoom est lié. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```

Obtient ou définit l'objet de section auquel l'objet Section Zoom est lié. Lecture/écriture [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)

Obtient ou définit l'objet de section auquel l'objet Section Zoom est lié. Lecture/écriture [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Cet exemple montre la modification de la section cible et crée une nouvelle image pour l'objet de zoom de section :
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |