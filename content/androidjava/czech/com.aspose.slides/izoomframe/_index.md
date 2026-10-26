---
title: IZoomFrame
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje objekt Slide Zoom ve snímku.
type: docs
url: /cs/com.aspose.slides/izoomframe/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Reprezentuje objekt Slide Zoom ve snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Získává nebo nastavuje objekt snímku, na který odkazuje objekt Slide Zoom. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Získává nebo nastavuje objekt snímku, na který odkazuje objekt Slide Zoom. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


Získává nebo nastavuje objekt snímku, na který odkazuje objekt Slide Zoom. Čtení/Zápis [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Vrací:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public abstract void setTargetSlide(ISlide value)
```


Získává nebo nastavuje objekt snímku, na který odkazuje objekt Slide Zoom. Čtení/Zápis [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Další příklad ukazuje změnu cílového snímku a vytváří nový obrázek pro objekt Slide Zoom:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |