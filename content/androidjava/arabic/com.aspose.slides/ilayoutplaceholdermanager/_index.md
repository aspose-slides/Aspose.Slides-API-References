---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Android via Java API Reference
description: يمثل مديرًا يسمح لك بإضافة عناصر نائب إلى شريحة التخطيط.
type: docs
url: /ar/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

يمثل مديرًا يسمح لك بإضافة عناصر نائب إلى شريحة التخطيط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ المحتوى، مثل صورة أو جدول أو وسائط أو نص. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ المحتوى، مثل صورة أو جدول أو وسائط أو نص في اتجاه عمودي. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ محتوى النص. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ محتوى النص في اتجاه عمودي. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ صورة. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ مخطط. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ جدول. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ مخطط SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ كائن وسائط. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ صورة عبر الإنترنت. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ المحتوى، مثل صورة أو جدول أو وسائط أو نص.

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
| x | float | إحداثي X للعنصر النائب الجديد. |
| y | float | إحداثي Y للعنصر النائب الجديد. |
| width | float | عرض العنصر النائب الجديد. |
| height | float | ارتفاع العنصر النائب الجديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب للمحتوى.  
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ المحتوى، مثل صورة أو جدول أو وسائط أو نص في اتجاه عمودي.

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
| x | float | إحداثي X للعنصر النائب الجديد. |
| y | float | إحداثي Y للعنصر النائب الجديد. |
| width | float | عرض العنصر النائب الجديد. |
| height | float | ارتفاع العنصر النائب الجديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب للمحتوى (عمودي).  
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ محتوى النص.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للعنصر النائب الجديد. |
| y | float | إحداثي Y للعنصر النائب الجديد. |
| width | float | عرض العنصر النائب الجديد. |
| height | float | ارتفاع العنصر النائب الجديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب للنص.  
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ محتوى النص في اتجاه عمودي.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للعنصر النائب الجديد. |
| y | float | إحداثي Y للعنصر النائب الجديد. |
| width | float | عرض العنصر النائب الجديد. |
| height | float | ارتفاع العنصر النائب الجديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب للنص (عمودي).  
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ صورة.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للعنصر النائب الجديد. |
| y | float | إحداثي Y للعنصر النائب الجديد. |
| width | float | عرض العنصر النائب الجديد. |
| height | float | ارتفاع العنصر النائب الجديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب للصورة.  
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ مخطط.

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
| x | float | إحداثي X للعنصر النائب الجديد. |
| y | float | إحداثي Y للعنصر النائب الجديد. |
| width | float | عرض العنصر النائب الجديد. |
| height | float | ارتفاع العنصر النائب الجديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب للمخطط.  
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ جدول.

--------------------

> ```
> المثال التالي يوضح كيفية إضافة شكل العنصر النائب للجدول إلى شريحة التخطيط.
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
| x | float | إحداثي X للعنصر النائب الجديد. |
| y | float | إحداثي Y للعنصر النائب الجديد. |
| width | float | عرض العنصر النائب الجديد. |
| height | float | ارتفاع العنصر النائب الجديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب للجدول.  
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ مخطط SmartArt.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للعنصر النائب الجديد. |
| y | float | إحداثي Y للعنصر النائب الجديد. |
| width | float | عرض العنصر النائب الجديد. |
| height | float | ارتفاع العنصر النائب الجديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب لـ SmartArt.  
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ كائن وسائط.

--------------------

> ```
> المثال التالي يوضح كيفية إضافة شكل العنصر النائب للوسائط إلى شريحة التخطيط.
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
| x | float | إحداثي X للعنصر النائب الجديد. |
| y | float | إحداثي Y للعنصر النائب الجديد. |
| width | float | عرض العنصر النائب الجديد. |
| height | float | ارتفاع العنصر النائب الجديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب للوسائط.  
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً عنصرًا نائبًا جديدًا إلى شريحة التخطيط لحفظ صورة عبر الإنترنت.

--------------------

> ```
> المثال التالي يوضح كيفية إضافة شكل العنصر النائب للصورة عبر الإنترنت إلى شريحة التخطيط.
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
| x | float | إحداثي X للعنصر النائب الجديد. |
| y | float | إحداثي Y للعنصر النائب الجديد. |
| width | float | عرض العنصر النائب الجديد. |
| height | float | ارتفاع العنصر النابع الجديد. |

**القيم المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب لصورة عبر الإنترنت.