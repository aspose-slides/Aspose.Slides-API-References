---
title: ISectionZoomFrame
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Reprezentuje obiekt Section Zoom na slajdzie.
type: docs
url: /pl/com.aspose.slides/isectionzoomframe/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

Reprezentuje obiekt Section Zoom na slajdzie.
## Metody

| Metoda | Opis |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Pobiera lub ustawia obiekt sekcji, do którego powiązany jest obiekt Section Zoom. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Pobiera lub ustawia obiekt sekcji, do którego powiązany jest obiekt Section Zoom. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```

Pobiera lub ustawia obiekt sekcji, do którego powiązany jest obiekt Section Zoom. Odczyt/zapis [ISection](../../com.aspose.slides/isection).

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

**Zwraca:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```

Pobiera lub ustawia obiekt sekcji, do którego powiązany jest obiekt Section Zoom. Odczyt/zapis [ISection](../../com.aspose.slides/isection).

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |