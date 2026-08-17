---
title: ZoomObject
second_title: Справочник API Aspose.Slides для Java
description: Представляет объект Zoom на слайде.
type: docs
url: /ru/com.aspose.slides/zoomobject/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

Представляет объект Zoom на слайде.

## Методы

| Метод | Описание |
| --- | --- |
| [getImageType()](#getImageType--) | Получает или задает тип изображения объекта Zoom. |
| [setImageType(int value)](#setImageType-int-) | Получает или задает тип изображения объекта Zoom. |
| [getReturnToParent()](#getReturnToParent--) | Получает или задает поведение навигации в показе слайдов. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Получает или задает поведение навигации в показе слайдов. |
| [getShowBackground()](#getShowBackground--) | Получает или задает значение, указывающее, будет ли Zoom использовать фон целевого слайда. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Получает или задает значение, указывающее, будет ли Zoom использовать фон целевого слайда. |
| [getZoomImage()](#getZoomImage--) | Получает или задает изображение для объекта Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Получает или задает изображение для объекта Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Получает или задает длительность перехода между Zoom и слайдом. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Получает или задает длительность перехода между Zoom и слайдом. |

### getImageType() {#getImageType--}
```
public final int getImageType()
```

Получает или задает тип изображения объекта Zoom. Чтение/запись [ZoomImageType](../../com.aspose.slides/zoomimagetype). Значение по умолчанию: Preview

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


--------------------

Указывает, использует ли объект Zoom предварительный просмотр слайда или изображение обложки.

**Возвращаемое значение:**
int

### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

Получает или задает тип изображения объекта Zoom. Чтение/запись [ZoomImageType](../../com.aspose.slides/zoomimagetype). Значение по умолчанию: Preview

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


--------------------

Указывает, использует ли объект Zoom предварительный просмотр слайда или изображение обложки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

Получает или задает поведение навигации в показе слайдов. Чтение/запись boolean. Значение по умолчанию: false

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


--------------------

Истинное значение свойства указывает возврат к навигации родителя в показе слайдов.

**Возвращаемое значение:**
boolean

### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

Получает или задает поведение навигации в показе слайдов. Чтение/запись boolean. Значение по умолчанию: false

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

--------------------

Истинное значение свойства указывает возврат к навигации родителя в показе слайдов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

Получает или задает значение, указывающее, будет ли Zoom использовать фон целевого слайда. Чтение/запись boolean. Значение по умолчанию: true

--------------------

> ```
> the example demonstrates removing the background of an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
boolean

### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public final void setShowBackground(boolean value)
```

Получает или задает значение, указывающее, будет ли Zoom использовать фон целевого слайда. Чтение/запись boolean. Значение по умолчанию: true

--------------------

> ```
> the example demonstrates removing the background of an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```

Получает или задает изображение для объекта Zoom. Чтение/запись [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> the example demonstrates changing an image of a Zoom object:
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

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage)

### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```

Получает или задает изображение для объекта Zoom. Чтение/запись [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> the example demonstrates changing an image of a Zoom object:
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

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
```

Получает или задает длительность перехода между Zoom и слайдом. Чтение/запись float. Значение по умолчанию: 1.0f

--------------------

> ```
> пример демонстрирует изменение длительности перехода между Zoom и слайдом:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Если не указано (TransitionDur = 0), будет использоваться переход целевого слайда и тайминг, связанный с этим переходом.

**Возвращаемое значение:**
float

### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

Получает или задает длительность перехода между Zoom и слайдом. Чтение/запись float. Значение по умолчанию: 1.0f

--------------------

> ```
> пример демонстрирует изменение длительности перехода между Zoom и слайдом:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Если не указано (TransitionDur = 0), будет использоваться переход целевого слайда и тайминг, связанный с этим переходом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |