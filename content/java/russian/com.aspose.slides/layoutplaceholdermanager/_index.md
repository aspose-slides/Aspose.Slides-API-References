---
title: LayoutPlaceholderManager
second_title: Справочник API Aspose.Slides для Java
description: Представляет менеджер, позволяющий добавлять заполняющие места в слайд-шаблон.
type: docs
url: /ru/com.aspose.slides/layoutplaceholdermanager/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Представляет менеджер, позволяющий добавлять заполняющие места в слайд-шаблон.
## Методы

| Метод | Описание |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Добавляет новую форму заполняющего места на слайде-шаблоне для размещения содержимого, например изображения, таблицы, медиа-объекта или текста. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Добавляет новую форму заполняющего места на слайде-шаблоне для размещения содержимого, например изображения, таблицы, медиа-объекта или текста в вертикальном направлении. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Добавляет новую форму заполняющего места на слайде-шаблоне для размещения текстового содержимого. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Добавляет новую форму заполняющего места на слайде-шаблоне для размещения текстового содержимого в вертикальном направлении. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Добавляет новую форму заполняющего места на слайде-шаблоне для размещения изображения. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Добавляет новую форму заполняющего места на слайде-шаблоне для размещения диаграммы. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Добавляет новую форму заполняющего места на слайде-шаблоне для размещения таблицы. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Добавляет новую форму заполняющего места на слайде-шаблоне для размещения диаграммы SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Добавляет новую форму заполняющего места на слайде-шаблоне для размещения медиа-объекта. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Добавляет новую форму заполняющего места на слайде-шаблоне для размещения онлайн-изображения. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполняющего места на слайде-шаблоне для размещения содержимого, например изображения, таблицы, медиа-объекта или текста.

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addContentPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X новой формы заполняющего места. |
| y | float | Координата Y новой формы заполняющего места. |
| width | float | Ширина новой формы заполняющего места. |
| height | float | Высота новой формы заполняющего места. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем контента.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполняющего места на слайде-шаблоне для размещения содержимого, например изображения, таблицы, медиа-объекта или текста в вертикальном направлении.

--------------------

> ```
> The following example shows how to add the Content (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalContentPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X новой формы заполняющего места. |
| y | float | Координата Y новой формы заполняющего места. |
| width | float | Ширина новой формы заполняющего места. |
| height | float | Высота новой формы заполняющего места. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Content (Vertical).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполняющего места на слайде-шаблоне для размещения текстового содержимого.

--------------------

> ```
> The following example shows how to add the Text placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X новой формы заполняющего места. |
| y | float | Координата Y новой формы заполняющего места. |
| width | float | Ширина новой формы заполняющего места. |
| height | float | Высота новой формы заполняющего места. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с текстовым заполнителем.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполняющего места на слайде-шаблоне для размещения текстового содержимого в вертикальном направлении.

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X новой формы заполняющего места. |
| y | float | Координата Y новой формы заполняющего места. |
| width | float | Ширина новой формы заполняющего места. |
| height | float | Высота новой формы заполняющего места. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с вертикальным текстовым заполнителем.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполняющего места на слайде-шаблоне для размещения изображения.

--------------------

> ```
> The following example shows how to add the Picture placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addPicturePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X новой формы заполняющего места. |
| y | float | Координата Y новой формы заполняющего места. |
| width | float | Ширина новой формы заполняющего места. |
| height | float | Высота новой формы заполняющего места. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем изображения.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполняющего места на слайде-шаблоне для размещения диаграммы.

--------------------

> ```
> The following example shows how to add the Chart placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addChartPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X новой формы заполняющего места. |
| y | float | Координата Y новой формы заполняющего места. |
| width | float | Ширина новой формы заполняющего места. |
| height | float | Высота новой формы заполняющего места. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем диаграммы.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполняющего места на слайде-шаблоне для размещения таблицы.

--------------------

> ```
> The following example shows how to add the Table placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTablePlaceholder(20, 20, 500, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X новой формы заполняющего места. |
| y | float | Координата Y новой формы заполняющего места. |
| width | float | Ширина новой формы заполняющего места. |
| height | float | Высота новой формы заполняющего места. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем таблицы.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполняющего места на слайде-шаблоне для размещения диаграммы SmartArt.

--------------------

> ```
> The following example shows how to add the SmartArt placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X новой формы заполняющего места. |
| y | float | Координата Y новой формы заполняющего места. |
| width | float | Ширина новой формы заполняющего места. |
| height | float | Высота новой формы заполняющего места. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем SmartArt.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполняющего места на слайде-шаблоне для размещения медиа-объекта.

--------------------

> ```
> The following example shows how to add the Media placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X новой формы заполняющего места. |
| y | float | Координата Y новой формы заполняющего места. |
| width | float | Ширина новой формы заполняющего места. |
| height | float | Высота новой формы заполняющего места. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем мультимедиа.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполняющего места на слайде-шаблоне для размещения онлайн-изображения.

--------------------

> ```
> The following example shows how to add the Online Image placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X новой формы заполняющего места. |
| y | float | Координата Y новой формы заполняющего места. |
| width | float | Ширина новой формы заполняющего места. |
| height | float | Высота новой формы заполняющего места. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем онлайн-изображения.