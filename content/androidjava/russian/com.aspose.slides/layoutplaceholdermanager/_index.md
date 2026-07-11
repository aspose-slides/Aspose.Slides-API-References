---
title: LayoutPlaceholderManager
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет менеджер, позволяющий добавлять заполнители на слайд макета.
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

Представляет менеджер, позволяющий добавлять заполнители на слайд макета.
## Методы

| Метод | Описание |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на слайд макета для размещения контента, такого как изображение, таблица, медиа или текст. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на слайд макета для размещения контента, такого как изображение, таблица, медиа или текст в вертикальном направлении. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на слайд макета для размещения текстового контента. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на слайд макета для размещения текстового контента в вертикальном направлении. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на слайд макета для размещения изображения. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на слайд макета для размещения диаграммы. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на слайд макета для размещения таблицы. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на слайд макета для размещения диаграммы SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на слайд макета для размещения медиа-объекта. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на слайд макета для размещения изображения из интернета. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Добавляет новую форму заполнителя на слайд макета для размещения контента, такого как изображение, таблица, медиа или текст.

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
| x | float | Координата X новой формы заполнителя. |
| y | float | Координата Y новой формы заполнителя. |
| width | float | Ширина новой формы заполнителя. |
| height | float | Высота новой формы заполнителя. |

**Возврат:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Content.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Добавляет новую форму заполнителя на слайд макета для размещения контента, такого как изображение, таблица, медиа или текст в вертикальном направлении.

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
| x | float | Координата X новой формы заполнителя. |
| y | float | Координата Y новой формы заполнителя. |
| width | float | Ширина новой формы заполнителя. |
| height | float | Высота новой формы заполнителя. |

**Возврат:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Content (Vertical).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Добавляет новую форму заполнителя на слайд макета для размещения текстового контента.

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
| x | float | Координата X новой формы заполнителя. |
| y | float | Координата Y новой формы заполнителя. |
| width | float | Ширина новой формы заполнителя. |
| height | float | Высота новой формы заполнителя. |

**Возврат:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Text.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Добавляет новую форму заполнителя на слайд макета для размещения текстового контента в вертикальном направлении.

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
| x | float | Координата X новой формы заполнителя. |
| y | float | Координата Y новой формы заполнителя. |
| width | float | Ширина новой формы заполнителя. |
| height | float | Высота новой формы заполнителя. |

**Возврат:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Text (Vertical).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Добавляет новую форму заполнителя на слайд макета для размещения изображения.

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
| x | float | Координата X новой формы заполнителя. |
| y | float | Координата Y новой формы заполнителя. |
| width | float | Ширина новой формы заполнителя. |
| height | float | Высота новой формы заполнителя. |

**Возврат:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Picture.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Добавляет новую форму заполнителя на слайд макета для размещения диаграммы.

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
| x | float | Координата X новой формы заполнителя. |
| y | float | Координата Y новой формы заполнителя. |
| width | float | Ширина новой формы заполнителя. |
| height | float | Высота новой формы заполнителя. |

**Возврат:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Chart.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Добавляет новую форму заполнителя на слайд макета для размещения таблицы.

--------------------

> ```
> Следующий пример демонстрирует, как добавить форму заполнителя Table на слайд макета.
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
| x | float | Координата X новой формы заполнителя. |
| y | float | Координата Y новой формы заполнителя. |
| width | float | Ширина новой формы заполнителя. |
| height | float | Высота новой формы заполнителя. |

**Возврат:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Table.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Добавляет новую форму заполнителя на слайд макета для размещения диаграммы SmartArt.

--------------------

> ```
> Следующий пример демонстрирует, как добавить форму заполнителя SmartArt на слайд макета.
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
| x | float | Координата X новой формы заполнителя. |
| y | float | Координата Y новой формы заполнителя. |
| width | float | Ширина новой формы заполнителя. |
| height | float | Высота новой формы заполнителя. |

**Возврат:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем SmartArt.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Добавляет новую форму заполнителя на слайд макета для размещения медиа-объекта.

--------------------

> ```
> Следующий пример демонстрирует, как добавить форму заполнителя Media на слайд макета.
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
| x | float | Координата X новой формы заполнителя. |
| y | float | Координата Y новой формы заполнителя. |
| width | float | Ширина новой формы заполнителя. |
| height | float | Высота новой формы заполнителя. |

**Возврат:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Media.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Добавляет новую форму заполнителя на слайд макета для размещения изображения из интернета.

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
| x | float | Координата X новой формы заполнителя. |
| y | float | Координата Y новой формы заполнителя. |
| width | float | Ширина новой формы заполнителя. |
| height | float | Высота новой формы заполнителя. |

**Возврат:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Online Image.