---
title: ZoomObject
second_title: Aspose.Slides dla Java - odniesienie API
description: Reprezentuje obiekt Zoom na slajdzie.
type: docs
url: /pl/com.aspose.slides/zoomobject/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

Reprezentuje obiekt Zoom na slajdzie.
## Metody

| Metoda | Opis |
| --- | --- |
| [getImageType()](#getImageType--) | Pobiera lub ustawia typ obrazu obiektu Zoom. |
| [setImageType(int value)](#setImageType-int-) | Pobiera lub ustawia typ obrazu obiektu Zoom. |
| [getReturnToParent()](#getReturnToParent--) | Pobiera lub ustawia zachowanie nawigacji w pokazie slajdów. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Pobiera lub ustawia zachowanie nawigacji w pokazie slajdów. |
| [getShowBackground()](#getShowBackground--) | Pobiera lub ustawia wartość określającą, czy Zoom użyje tła docelowego slajdu. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Pobiera lub ustawia wartość określającą, czy Zoom użyje tła docelowego slajdu. |
| [getZoomImage()](#getZoomImage--) | Pobiera lub ustawia obraz dla obiektu Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Pobiera lub ustawia obraz dla obiektu Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Pobiera lub ustawia czas trwania przejścia między Zoomem a slajdem. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Pobiera lub ustawia czas trwania przejścia między Zoomem a slajdem. |
### getImageType() {#getImageType--}
```
public final int getImageType()
```

Pobiera lub ustawia typ obrazu obiektu Zoom. Odczyt/zapis [ZoomImageType](../../com.aspose.slides/zoomimagetype). Domyślna wartość: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Specifies whether the Zoom object is using the slide preview or a cover image.

**Zwraca:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

Pobiera lub ustawia typ obrazu obiektu Zoom. Odczyt/zapis [ZoomImageType](../../com.aspose.slides/zoomimagetype). Domyślna wartość: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Specifies whether the Zoom object is using the slide preview or a cover image.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

Pobiera lub ustawia zachowanie nawigacji w pokazie slajdów. Odczyt/zapis boolean. Domyślna wartość: false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Prawdziwa wartość tej właściwości określa zachowanie powrotu do rodzica w pokazie slajdów.

**Zwraca:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

Pobiera lub ustawia zachowanie nawigacji w pokazie slajdów. Odczyt/zapis boolean. Domyślna wartość: false

--------------------

> ```
> Przykład:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Prawdziwa wartość tej właściwości określa zachowanie powrotu do rodzica w pokazie slajdów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

Pobiera lub ustawia wartość określającą, czy Zoom użyje tła docelowego slajdu. Odczyt/zapis boolean. Domyślna wartość: true

--------------------

> ```
> przykład demonstruje usunięcie tła obrazu obiektu Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public final void setShowBackground(boolean value)
```

Pobiera lub ustawia wartość określającą, czy Zoom użyje tła docelowego slajdu. Odczyt/zapis boolean. Domyślna wartość: true

--------------------

> ```
> przykład demonstruje usunięcie tła obrazu obiektu Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```

Pobiera lub ustawia obraz dla obiektu Zoom. Odczyt/zapis [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> przykład demonstruje zmianę obrazu obiektu Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```

Pobiera lub ustawia obraz dla obiektu Zoom. Odczyt/zapis [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> przykład demonstruje zmianę obrazu obiektu Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
```

Pobiera lub ustawia czas trwania przejścia między Zoomem a slajdem. Odczyt/zapis float. Domyślna wartość: 1.0f

--------------------

> ```
> przykład demonstruje zmianę czasu trwania przejścia między Zoom a slajdem:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Jeśli nie zostanie określone (TransitionDur = 0), zostanie użyte przejście slajdu docelowego oraz czasy powiązane z tym przejściem.

**Zwraca:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

Pobiera lub ustawia czas trwania przejścia między Zoomem a slajdem. Odczyt/zapis float. Domyślna wartość: 1.0f

--------------------

> ```
> przykład demonstruje zmianę czasu trwania przejścia między Zoom a slajdem:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Jeśli nie zostanie określone (TransitionDur = 0), zostanie użyte przejście slajdu docelowego oraz czasy powiązane z tym przejściem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |