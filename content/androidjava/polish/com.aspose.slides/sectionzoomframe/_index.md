---
title: SectionZoomFrame
second_title: Aspose.Slides dla Androida – odniesienie do API Java
description: Reprezentuje obiekt Section Zoom na slajdzie.
type: docs
url: /pl/com.aspose.slides/sectionzoomframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**All Implemented Interfaces:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

Reprezentuje obiekt Section Zoom na slajdzie.
## Metody

| Metoda | Opis |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Pobiera lub ustawia obiekt sekcji, do którego odwołuje się obiekt Section Zoom. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Pobiera lub ustawia obiekt sekcji, do którego odwołuje się obiekt Section Zoom. |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```

Pobiera lub ustawia obiekt sekcji, do którego odwołuje się obiekt Section Zoom. Odczyt/zapis [ISection](../../com.aspose.slides/isection).

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

**Zwraca:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```

Pobiera lub ustawia obiekt sekcji, do którego odwołuje się obiekt Section Zoom. Odczyt/zapis [ISection](../../com.aspose.slides/isection).

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |