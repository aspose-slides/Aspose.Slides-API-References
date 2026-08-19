---
title: ISectionZoomFrame
second_title: Aspose.Slides pro Java – referenční příručka API
description: Zastupuje objekt Section Zoom na snímku.
type: docs
url: /cs/com.aspose.slides/isectionzoomframe/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

Zastupuje objekt Section Zoom na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Získá nebo nastaví objekt sekce, ke kterému je objekt Section Zoom odkazován. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Získá nebo nastaví objekt sekce, ke kterému je objekt Section Zoom odkazován. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```


Získá nebo nastaví objekt sekce, ke kterému je objekt Section Zoom odkazován. Čtení/zápis [ISection](../../com.aspose.slides/isection).

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

**Vrací:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```


Získá nebo nastaví objekt sekce, ke kterému je objekt Section Zoom odkazován. Čtení/zápis [ISection](../../com.aspose.slides/isection).

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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |