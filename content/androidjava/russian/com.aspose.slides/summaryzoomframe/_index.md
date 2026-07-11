---
title: SummaryZoomFrame
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет объект Summary Zoom на слайде.
type: docs
url: /ru/com.aspose.slides/summaryzoomframe/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

Представляет объект Summary Zoom на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [getLayout()](#getLayout--) | Получает расположение разделов Summary Zoom во фрейме. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Получает [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) для объекта Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public final int getLayout()
```


Получает расположение разделов Summary Zoom во фрейме. Значение по умолчанию — GridLayout.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Получает [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) для объекта Summary Zoom Frame.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)