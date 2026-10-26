---
title: IZoomFrame
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente un objet Slide Zoom dans une diapositive.
type: docs
url: /fr/com.aspose.slides/izoomframe/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Représente un objet Slide Zoom dans une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Obtient ou définit l'objet slide auquel l'objet Slide Zoom se lie. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Obtient ou définit l'objet slide auquel l'objet Slide Zoom se lie. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


Obtient ou définit l'objet slide auquel l'objet Slide Zoom se lie. Lecture/écriture [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Returns:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public abstract void setTargetSlide(ISlide value)


Obtient ou définit l'objet slide auquel l'objet Slide Zoom se lie. Lecture/écriture [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> L'exemple suivant montre comment changer la diapositive cible et crée une nouvelle image pour l'objet Slide Zoom :
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |