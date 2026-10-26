---
title: SummaryZoomSection
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет объект Summary Zoom Section в кадре Summary Zoom.
type: docs
url: /ru/com.aspose.slides/summaryzoomsection/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject), [com.aspose.slides.SectionZoomFrame](../../com.aspose.slides/sectionzoomframe)

**Все реализованные интерфейсы:**
[com.aspose.slides.ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
```
public class SummaryZoomSection extends SectionZoomFrame implements ISummaryZoomSection
```

Представляет объект Summary Zoom Section в кадре Summary Zoom.

## Методы

| Метод | Описание |
| --- | --- |
| [getTitle()](#getTitle--) | Возвращает текстовый заголовок объекта Summary Zoom Section. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Возвращает текстовый заголовок объекта Summary Zoom Section. |
| [getDescription()](#getDescription--) | Возвращает текстовое описание объекта Summary Zoom Section. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Возвращает текстовое описание объекта Summary Zoom Section. |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

Возвращает текстовый заголовок объекта Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```

**Возвращает:**
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Возвращает текстовый заголовок объекта Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```

Возвращает текстовое описание объекта Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Возвращает:**
java.lang.String

### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```

Возвращает текстовое описание объекта Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |