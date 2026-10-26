---
title: ISummaryZoomFrame
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет кадр Summary Zoom в слайде.
type: docs
url: /ru/com.aspose.slides/isummaryzoomframe/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

Представляет кадр Summary Zoom в слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [getLayout()](#getLayout--) | Получает макет разделов Summary Zoom в кадре. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Получает [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) для объекта Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Получает макет разделов Summary Zoom в кадре. Значение по умолчанию — GridLayout.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Получает [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) для объекта Summary Zoom Frame.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)