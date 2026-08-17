---
title: IZoomObject
second_title: Справочник API Aspose.Slides для Java
description: Представляет объект Zoom на слайде.
type: docs
url: /ru/com.aspose.slides/izoomobject/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Представляет объект Zoom на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [getImageType()](#getImageType--) | Получает или задает тип изображения объекта Zoom. |
| [setImageType(int value)](#setImageType-int-) | Получает или задает тип изображения объекта Zoom. |
| [getReturnToParent()](#getReturnToParent--) | Получает или задает поведение навигации в режиме презентации. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Получает или задает поведение навигации в режиме презентации. |
| [getShowBackground()](#getShowBackground--) | Получает или задает значение, указывающее, будет ли Zoom использовать фон целевого слайда. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Получает или задает значение, указывающее, будет ли Zoom использовать фон целевого слайда. |
| [getZoomImage()](#getZoomImage--) | Получает или задает изображение для объекта Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Получает или задает изображение для объекта Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Получает или задает длительность перехода между Zoom и слайдом. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Получает или задает длительность перехода между Zoom и слайдом. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

Получает или задает тип изображения объекта Zoom. Чтение/запись [ZoomImageType](../../com.aspose.slides/zoomimagetype). Значение по умолчанию: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

Указывает, использует ли объект Zoom предварительный просмотр слайда или обложку.

**Возвращаемое значение:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

Получает или задает тип изображения объекта Zoom. Чтение/запись [ZoomImageType](../../com.aspose.slides/zoomimagetype). Значение по умолчанию: Preview

--------------------

> ```
> Этот пример демонстрирует изменение типа изображения на значение Preview. 
>  В этом случае текущее изображение объекта Zoom меняется на изображение слайда:
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

Указывает, использует ли объект Zoom предварительный просмотр слайда или обложку.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

Получает или задает поведение навигации в режиме презентации. Чтение/запись boolean. Значение по умолчанию: false

--------------------

> ```
> Пример:
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

Истинное значение свойства указывает возвращение к родительской навигации в режиме презентации.

**Возвращаемое значение:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

Получает или задает поведение навигации в режиме презентации. Чтение/запись boolean. Значение по умолчанию: false

--------------------

> ```
> Пример:
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

Истинное значение свойства указывает возвращение к родительской навигации в режиме презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

Получает или задает значение, указывающее, будет ли Zoom использовать фон целевого слайда. Чтение/запись boolean. Значение по умолчанию: true

--------------------

> ```
> Пример демонстрирует удаление фона изображения объекта Zoom:
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
public abstract void setShowBackground(boolean value)
```

Получает или задает значение, указывающее, будет ли Zoom использовать фон целевого слайда. Чтение/запись boolean. Значение по умолчанию: true

--------------------

> ```
> Пример демонстрирует удаление фона изображения объекта Zoom:
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
public abstract IPPImage getZoomImage()
```

Получает или задает изображение для объекта Zoom. Чтение/запись [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Пример демонстрирует изменение изображения объекта Zoom:
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
public abstract void setZoomImage(IPPImage value)
```

Получает или задает изображение для объекта Zoom. Чтение/запись [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Пример демонстрирует изменение изображения объекта Zoom:
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
public abstract float getTransitionDuration()
```

Получает или задает длительность перехода между Zoom и слайдом. Чтение/запись float. Значение по умолчанию: 1.0f

--------------------

> ```
> Пример демонстрирует изменение длительности перехода между Zoom и слайдом:
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

Если не указано (TransitionDur = 0), будет использован переход целевого слайда и связанные с ним тайминги.

**Возвращаемое значение:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

Получает или задает длительность перехода между Zoom и слайдом. Чтение/запись float. Значение по умолчанию: 1.0f

--------------------

> ```
> Пример демонстрирует изменение длительности перехода между Zoom и слайдом:
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

Если не указано (TransitionDur = 0), будет использован переход целевого слайда и связанные с ним тайминги.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |