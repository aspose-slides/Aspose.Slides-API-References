---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Java API Reference
description: Представляет менеджер, позволяющий добавлять заполнители в макетный слайд.
type: docs
url: /ru/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Представляет менеджер, позволяющий добавлять заполнители в макетный слайд.
## Методы

| Метод | Описание |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на макетный слайд для размещения содержимого, например изображения, таблицы, медиафайла или текста. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на макетный слайд для размещения содержимого, например изображения, таблицы, медиафайла или текста в вертикальном направлении. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на макетный слайд для размещения текстового содержимого. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на макетный слайд для размещения текстового содержимого в вертикальном направлении. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на макетный слайд для размещения изображения. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на макетный слайд для размещения диаграммы. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на макетный слайд для размещения таблицы. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на макетный слайд для размещения диаграммы SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на макетный слайд для размещения медиаобъекта. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Добавляет новую форму заполнителя на макетный слайд для размещения онлайн-изображения. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполнителя на макетный слайд для размещения содержимого, например изображения, таблицы, медиафайла или текста.

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  
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

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Content.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполнителя на макетный слайд для размещения содержимого, например изображения, таблицы, медиафайла или текста в вертикальном направлении.

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

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Content (Vertical).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполнителя на макетный слайд для размещения текстового содержимого.

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

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Text.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполнителя на макетный слайд для размещения текстового содержимого в вертикальном направлении.

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalTextPlaceholder(20, 20, 300, 500);
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

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Text (Vertical).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполнителя на макетный слайд для размещения изображения.

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

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Picture.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполнителя на макетный слайд для размещения диаграммы.

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

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Chart.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполнителя на макетный слайд для размещения таблицы.

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
| x | float | Координата X новой формы заполнителя. |
| y | float | Координата Y новой формы заполнителя. |
| width | float | Ширина новой формы заполнителя. |
| height | float | Высота новой формы заполнителя. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Table.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполнителя на макетный слайд для размещения диаграммы SmartArt.

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
| x | float | Координата X новой формы заполнителя. |
| y | float | Координата Y новой формы заполнителя. |
| width | float | Ширина новой формы заполнителя. |
| height | float | Высота новой формы заполнителя. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем SmartArt.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполнителя на макетный слайд для размещения медиаобъекта.

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
| x | float | Координата X новой формы заполнителя. |
| y | float | Координата Y новой формы заполнителя. |
| width | float | Ширина новой формы заполнителя. |
| height | float | Высота новой формы заполнителя. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Media.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


Добавляет новую форму заполнителя на макетный слайд для размещения онлайн-изображения.

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

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Создан [IAutoShape](../../com.aspose.slides/iautoshape) с заполнителем Online Image.