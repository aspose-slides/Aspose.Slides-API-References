---
title: LayoutPlaceholderManager
second_title: Aspose.Slides for Android عبر مرجع API جافا
description: يمثل مديرًا يتيح لك إضافة عناصر نائبة إلى شريحة التخطيط.
type: docs
url: /ar/com.aspose.slides/layoutplaceholdermanager/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)  
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

يمثل مديرًا يتيح لك إضافة عناصر نائبة إلى شريحة التخطيط.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء المحتوى، مثل صورة أو جدول أو وسائط أو نص. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء المحتوى، مثل صورة أو جدول أو وسائط أو نص في اتجاه عمودي. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء محتوى النص. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء محتوى النص في اتجاه عمودي. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء صورة. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء مخطط. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء جدول. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء مخطط SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء عنصر وسائط. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء صورة عبر الإنترنت. |

### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

يضيف شكلًا عنصرًا نابعًا جديدًا إلى شريحة التخطيط لاحتواء المحتوى، مثل صورة أو جدول أو وسائط أو نص.

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

**المُعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للشكل العنصر النائب الجديد. |
| y | float | إحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**القيمة المرجعة:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب للمحتوى.

### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء المحتوى، مثل صورة أو جدول أو وسائط أو نص في اتجاه عمودي.

--------------------

> ```
> يوضح المثال التالي كيفية إضافة شكل العنصر النائب Content (Vertical) إلى شريحة التخطيط.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalContentPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المُعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للشكل العنصر النائب الجديد. |
| y | float | إحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**القيمة المرجعة:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب للمحتوى (عمودي).

### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء محتوى النص.

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

**المُعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للشكل العنصر النائب الجديد. |
| y | float | إحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**القيمة المرجعة:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب للنص.

### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء محتوى النص في اتجاه عمودي.

--------------------

> ```
> يوضح المثال التالي كيفية إضافة شكل العنصر النائب Text (Vertical) إلى شريحة التخطيط.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المُعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للشكل العنصر النائب الجديد. |
| y | float | إحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**القيمة المرجعة:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب للنص (عمودي).

### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء صورة.

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

**المُعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للشكل العنصر النائب الجديد. |
| y | float | إحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**القيمة المرجعة:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب للصورة.

### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء مخطط.

--------------------

> ```
> يوضح المثال التالي كيفية إضافة شكل العنصر النائب Chart إلى شريحة التخطيط.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addChartPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المُعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للشكل العنصر النائب الجديد. |
| y | float | إحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**القيمة المرجعة:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب للمخطط.

### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء جدول.

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

**المُعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للشكل العنصر النائب الجديد. |
| y | float | إحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائيب الجديد. |

**القيمة المرجعة:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب للجدول.

### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء مخطط SmartArt.

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

**المُعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للشكل العنصر النائب الجديد. |
| y | float | إحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**القيمة المرجعة:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب لـ SmartArt.

### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء عنصر وسائط.

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

**المُعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للشكل العنصر النائب الجديد. |
| y | float | إحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**القيمة المرجعة:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب للوسائط.

### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

يضيف شكلًا عنصرًا نائبًا جديدًا إلى شريحة التخطيط لاحتواء صورة عبر الإنترنت.

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

**المُعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي X للشكل العنصر النائب الجديد. |
| y | float | إحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**القيمة المرجعة:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب لصورة عبر الإنترنت.