---
title: LayoutPlaceholderManager
second_title: Aspose.Slides لمرجع API جافا
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

يمثل مديرًا يسمح لك بإضافة عناصر نائبة إلى شريحة التخطيط.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء المحتوى، مثل صورة أو جدول أو وسائط أو نص. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء المحتوى، مثل صورة أو جدول أو وسائط أو نص في اتجاه عمودي. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء محتوى نصي. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء محتوى نصي في اتجاه عمودي. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء صورة. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء مخطط. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء جدول. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء مخطط SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء كائن وسائط. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء صورة على الإنترنت. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء المحتوى، مثل صورة أو جدول أو وسائط أو نص.

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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X للشكل العنصر النائب الجديد. |
| y | float | الإحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**الإرجاع:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من النوع Content.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء المحتوى، مثل صورة أو جدول أو وسائط أو نص في اتجاه عمودي.

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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X للشكل العنصر النائب الجديد. |
| y | float | الإحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**الإرجاع:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من النوع Content (Vertical).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء محتوى نصي.

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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X للشكل العنصر النائب الجديد. |
| y | float | الإحداثي Y للشكل العنصر النابع الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**الإرجاع:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من النوع Text.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء محتوى نصي في اتجاه عمودي.

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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X للشكل العنصر النائب الجديد. |
| y | float | الإحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**الإرجاع:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من النوع Text (Vertical).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء صورة.

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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X للشكل العنصر النائب الجديد. |
| y | float | الإحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**الإرجاع:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من النوع Picture.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء مخطط.

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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X للشكل العنصر النائب الجديد. |
| y | float | الإحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**الإرجاع:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من النوع Chart.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء جدول.

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X للشكل العنصر النائب الجديد. |
| y | float | الإحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**الإرجاع:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من النوع Table.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء مخطط SmartArt.

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X للشكل العنصر النائب الجديد. |
| y | float | الإحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**الإرجاع:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من النوع SmartArt.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء كائن وسائط.

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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X للشكل العنصر النائب الجديد. |
| y | float | الإحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**الإرجاع:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من النوع Media.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

يضيف شكلاً جديدًا عنصرًا نائبًا إلى شريحة التخطيط لاحتواء صورة على الإنترنت.

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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X للشكل العنصر النائب الجديد. |
| y | float | الإحداثي Y للشكل العنصر النائب الجديد. |
| width | float | عرض الشكل العنصر النائب الجديد. |
| height | float | ارتفاع الشكل العنصر النائب الجديد. |

**الإرجاع:**
[IAutoShape](../../com.aspose.slides/iautoshape) - تم إنشاء [IAutoShape](../../com.aspose.slides/iautoshape) مع عنصر نائب من النوع Online Image.