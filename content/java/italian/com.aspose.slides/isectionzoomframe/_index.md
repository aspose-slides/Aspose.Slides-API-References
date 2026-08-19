---
title: ISectionZoomFrame
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un oggetto Section Zoom in una diapositiva.
type: docs
url: /it/com.aspose.slides/isectionzoomframe/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

Rappresenta un oggetto Section Zoom in una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Ottiene o imposta l'oggetto sezione a cui è collegato l'oggetto Section Zoom. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Ottiene o imposta l'oggetto sezione a cui è collegato l'oggetto Section Zoom. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```


Ottiene o imposta l'oggetto sezione a cui è collegato l'oggetto Section Zoom. Lettura/scrittura [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Questo esempio dimostra la modifica della sezione di destinazione e crea una nuova immagine per l'oggetto Section Zoom:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```


Ottiene o imposta l'oggetto sezione a cui è collegato l'oggetto Section Zoom. Lettura/scrittura [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Questo esempio dimostra la modifica della sezione di destinazione e crea una nuova immagine per l'oggetto Section Zoom:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |