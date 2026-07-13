---
title: IZoomFrame
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta un oggetto Slide Zoom in una diapositiva.
type: docs
url: /it/com.aspose.slides/izoomframe/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Rappresenta un oggetto Slide Zoom in una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Ottiene o imposta l'oggetto slide a cui l'oggetto Slide Zoom è collegato. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Ottiene o imposta l'oggetto slide a cui l'oggetto Slide Zoom è collegato. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Ottiene o imposta l'oggetto slide a cui l'oggetto Slide Zoom è collegato. Lettura/scrittura [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Il prossimo esempio dimostra come modificare la diapositiva di destinazione e crea una nuova immagine per l'oggetto Slide Zoom:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
```

**Restituisce:**  
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public abstract void setTargetSlide(ISlide value)
```

Ottiene o imposta l'oggetto slide a cui l'oggetto Slide Zoom è collegato. Lettura/scrittura [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Il prossimo esempio dimostra come modificare la diapositiva di destinazione e crea una nuova immagine per l'oggetto Slide Zoom:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |