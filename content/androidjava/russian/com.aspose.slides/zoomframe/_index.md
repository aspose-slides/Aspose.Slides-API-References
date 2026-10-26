---
title: ZoomFrame
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет объект Slide Zoom на слайде.
type: docs
url: /ru/com.aspose.slides/zoomframe/
---
**Наследование:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Все реализованные интерфейсы:**  
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)  
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

Представляет объект Slide Zoom на слайде.

## Методы

| Метод | Описание |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Получает или задает объект слайда, к которому объект Slide Zoom привязан. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Получает или задает объект слайда, к которому объект Slide Zoom привязан. |

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Получает или задает объект слайда, к которому объект Slide Zoom привязан. Чтение/запись [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Возвращаемое значение:**  
[ISlide](../../com.aspose.slides/islide)

### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public final void setTargetSlide(ISlide value)
```

Получает или задает объект слайда, к которому объект Slide Zoom привязан. Чтение/запись [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |