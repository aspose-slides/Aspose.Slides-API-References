---
title: IZoomObject
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje obiekt Zoom na slajdzie.
type: docs
url: /pl/com.aspose.slides/izoomobject/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Reprezentuje obiekt Zoom na slajdzie.
## Metody

| Metoda | Opis |
| --- | --- |
| [getImageType()](#getImageType--) | Pobiera lub ustawia typ obrazu obiektu zoom. |
| [setImageType(int value)](#setImageType-int-) | Pobiera lub ustawia typ obrazu obiektu zoom. |
| [getReturnToParent()](#getReturnToParent--) | Pobiera lub ustawia zachowanie nawigacji w pokazie slajdów. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Pobiera lub ustawia zachowanie nawigacji w pokazie slajdów. |
| [getShowBackground()](#getShowBackground--) | Pobiera lub ustawia wartość określającą, czy Zoom użyje tła docelowego slajdu. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Pobiera lub ustawia wartość określającą, czy Zoom użyje tła docelowego slajdu. |
| [getZoomImage()](#getZoomImage--) | Pobiera lub ustawia obraz dla obiektu zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Pobiera lub ustawia obraz dla obiektu zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Pobiera lub ustawia czas trwania przejścia między Zoom a slajdem. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Pobiera lub ustawia czas trwania przejścia między Zoom a slajdem. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

Pobiera lub ustawia typ obrazu obiektu zoom. Odczyt/zapis [ZoomImageType](../../com.aspose.slides/zoomimagetype). Wartość domyślna: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Określa, czy obiekt Zoom używa podglądu slajdu, czy obrazu okładki.

**Zwraca:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

Pobiera lub ustawia typ obrazu obiektu zoom. Odczyt/zapis [ZoomImageType](../../com.aspose.slides/zoomimagetype). Wartość domyślna: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Określa, czy obiekt Zoom używa podglądu slajdu, czy obrazu okładki.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

Pobiera lub ustawia zachowanie nawigacji w pokazie slajdów. Odczyt/zapis boolean. Wartość domyślna: false

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


--------------------

Wartość true właściwości określa zachowanie powrotu do rodzica w pokazie slajdów.

**Zwraca:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

Pobiera lub ustawia zachowanie nawigacji w pokazie slajdów. Odczyt/zapis boolean. Wartość domyślna: false

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


--------------------

Wartość true właściwości określa zachowanie powrotu do rodzica w pokazie slajdów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

Pobiera lub ustawia wartość określającą, czy Zoom użyje tła docelowego slajdu. Odczyt/zapis boolean. Wartość domyślna: true

--------------------

> ```
> Przykład demonstruje usunięcie tła obrazu obiektu Zoom:
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
public abstract void setShowBackground(boolean value)
```

Pobiera lub ustawia wartość określającą, czy Zoom użyje tła docelowego slajdu. Odczyt/zapis boolean. Wartość domyślna: true

--------------------

> ```
> The example demonstrates removing the background of an image of a Zoom object:
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
public abstract IPPImage getZoomImage()
```

Pobiera lub ustawia obraz dla obiektu zoom. Odczyt/zapis [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Przykład demonstruje zmianę obrazu obiektu Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```

Pobiera lub ustawia obraz dla obiektu zoom. Odczyt/zapis [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Przykład demonstruje zmianę obrazu obiektu Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
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
public abstract float getTransitionDuration()
```

Pobiera lub ustawia czas trwania przejścia między Zoom a slajdem. Odczyt/zapis float. Wartość domyślna: 1.0f

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


--------------------

Jeśli nie określono (TransitionDur = 0), zostanie użyte przejście docelowego slajdu oraz czasy związane z tym przejściem.

**Zwraca:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

Pobiera lub ustawia czas trwania przejścia między Zoom a slajdem. Odczyt/zapis float. Wartość domyślna: 1.0f

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


--------------------

Jeśli nie określono (TransitionDur = 0), zostanie użyte przejście docelowego slajdu oraz czasy związane z tym przejściem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |