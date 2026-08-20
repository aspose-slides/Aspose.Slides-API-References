---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Java API Reference
description: Represents manager that allows you to add placeholders to the layout slide.
type: docs
url: /ar/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

يمثل مديرًا يتيح لك إضافة عناصر نائبة إلى شريحة التخطيط.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل المحتوى، مثل صورة أو جدول أو وسائط أو نص. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل المحتوى، مثل صورة أو جدول أو وسائط أو نص في اتجاه عمودي. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل محتوى نصي. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل محتوى نصي في اتجاه عمودي. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل صورة. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل مخطط. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل جدول. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل مخطط SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل كائن وسائط. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل صورة عبر الإنترنت. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل المحتوى، مثل صورة أو جدول أو وسائط أو نص.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X لشكل العنصر النائب الجديد. |
| y | float | الإحداثي Y لشكل العنصر النائب الجديد. |
| width | float | عرض شكل العنصر النائب الجديد. |
| height | float | ارتفاع شكل العنصر النائب الجديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من نوع Content.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل المحتوى، مثل صورة أو جدول أو وسائط أو نص في اتجاه عمودي.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X لشكل العنصر النائب الجديد. |
| y | float | الإحداثي Y لشكل العنصر النائب الجديد. |
| width | float | عرض شكل العنصر النائب الجديد. |
| height | float | ارتفاع شكل العنصر النائب الجديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من نوع Content (Vertical).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل محتوى نصي.

--------------------

> ```
> يوضح المثال التالي كيفية إضافة شكل العنصر النائب Text إلى شريحة التخطيط.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X لشكل العنصر النائب الجديد. |
| y | float | الإحداثي Y لشكل العنصر النائب الجديد. |
| width | float | عرض شكل العنصر النائب الجديد. |
| height | float | ارتفاع شكل العنصر النائب الجديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من نوع Text.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل محتوى نصي في اتجاه عمودي.

--------------------

> ```
> يوضح المثال التالي كيفية إضافة شكل العنصر النائب Text (Vertical) إلى شريحة التخطيط.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalTextPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X لشكل العنصر النائب الجديد. |
| y | float | الإحداثي Y لشكل العنصر النائب الجديد. |
| width | float | عرض شكل العنصر النائب الجديد. |
| height | float | ارتفاع شكل العنصر النائب الجديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من نوع Text (Vertical).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل صورة.

--------------------

> ```
> يوضح المثال التالي كيفية إضافة شكل العنصر النائب Picture إلى شريحة التخطيط.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addPicturePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X لشكل العنصر النائب الجديد. |
| y | float | الإحداثي Y لشكل العنصر النائب الجديد. |
| width | float | عرض شكل العنصر النائب الجديد. |
| height | float | ارتفاع شكل العنصر النائب الجديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من نوع Picture.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل مخطط.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X لشكل العنصر النائب الجديد. |
| y | float | الإحداثي Y لشكل العنصر النائب الجديد. |
| width | float | عرض شكل العنصر النائب الجديد. |
| height | float | ارتفاع شكل العنصر النائب الجديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من نوع Chart.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل جدول.

--------------------

> ```
> يوضح المثال التالي كيفية إضافة شكل العنصر النائب Table إلى شريحة التخطيط.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTablePlaceholder(20, 20, 500, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X لشكل العنصر النائب جديد. |
| y | float | الإحداثي Y لشكل العنصر النائب جديد. |
| width | float | عرض شكل العنصر النائب جديد. |
| height | float | ارتفاع شكل العنصر النائب جديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من نوع Table.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل مخطط SmartArt.

--------------------

> ```
> يوضح المثال التالي كيفية إضافة شكل العنصر النائب SmartArt إلى شريحة التخطيط.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X لشكل العنصر النائب جديد. |
| y | float | الإحداثي Y لشكل العنصر النائب جديد. |
| width | float | عرض شكل العنصر النائب جديد. |
| height | float | ارتفاع شكل العنصر النائب جديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من نوع SmartArt.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل كائن وسائط.

--------------------

> ```
> يوضح المثال التالي كيفية إضافة شكل العنصر النائب Media إلى شريحة التخطيط.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X لشكل العنصر النائب جديد. |
| y | float | الإحداثي Y لشكل العنصر النائب جديد. |
| width | float | عرض شكل العنصر النائب جديد. |
| height | float | ارتفاع شكل العنصر النائب جديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من نوع Media.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


يضيف شكلًا نائبًا جديدًا إلى شريحة التخطيط لحمل صورة عبر الإنترنت.

--------------------

> ```
> يوضح المثال التالي كيفية إضافة شكل العنصر النائب Online Image إلى شريحة التخطيط.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X لشكل العنصر النائب جديد. |
| y | float | الإحداثي Y لشكل العنصر النائب جديد. |
| width | float | عرض شكل العنصر النائب جديد. |
| height | float | ارتفاع شكل العنصر النائب جديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من نوع Online Image.