---
title: SectionZoomFrame
second_title: Référence API Aspose.Slides pour Java
description: Représente un objet Section Zoom dans une diapositive.
type: docs
url: /fr/com.aspose.slides/sectionzoomframe/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Toutes les interfaces implémentées:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

Représente un objet Section Zoom dans une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Obtient ou définit l'objet section auquel l'objet Section Zoom fait référence. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Obtient ou définit l'objet section auquel l'objet Section Zoom fait référence. |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```


Obtient ou définit l'objet section auquel l'objet Section Zoom fait référence. Lecture/écriture [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> L'exemple suivant démontre la modification de la section cible et crée une nouvelle image pour l'objet Section Zoom :
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourne:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```


Obtient ou définit l'objet section auquel l'objet Section Zoom fait référence. Lecture/écriture [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Next example demonstrates changing target section and creates new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |