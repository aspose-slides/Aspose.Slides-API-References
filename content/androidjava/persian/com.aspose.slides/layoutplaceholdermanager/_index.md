---
title: LayoutPlaceholderManager
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: مدیری را نشان می‌دهد که به شما امکان افزودن مکان‌گیرها به اسلاید طرح‌بندی را می‌دهد.
type: docs
url: /fa/com.aspose.slides/layoutplaceholdermanager/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

مدیری را نشان می‌دهد که به شما امکان افزودن مکان‌گیرها به اسلاید طرح‌بندی را می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا محتوا، مانند تصویر، جدول، رسانه یا متن، را در خود نگه دارد. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا محتوا، مانند تصویر، جدول، رسانه یا متن، را به صورت عمودی در خود نگه دارد. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا محتواهای متنی را در خود نگه دارد. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا محتواهای متنی را به صورت عمودی در خود نگه دارد. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا یک تصویر را در خود نگه دارد. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا یک نمودار را در خود نگه دارد. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا یک جدول را در خود نگه دارد. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا یک نمودار SmartArt را در خود نگه دارد. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا یک شی رسانه‌ای را در خود نگه دارد. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا یک تصویر آنلاین را در خود نگه دارد. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا محتوا، مانند تصویر، جدول، رسانه یا متن، را در خود نگه دارد.

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


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات X شکل مکان‌گیر جدید. |
| y | float | مختصات Y شکل مکان‌گیر جدید. |
| width | float | عرض شکل مکان‌گیر جدید. |
| height | float | ارتفاع شکل مکان‌گیر جدید. |

**بازگشت:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شده [IAutoShape](../../com.aspose.slides/iautoshape) با یک مکان‌گیر محتوا.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا محتوا، مانند تصویر، جدول، رسانه یا متن، را به صورت عمودی در خود نگه دارد.

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


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات X شکل مکان‌گیر جدید. |
| y | float | مختصات Y شکل مکان‌گیر جدید. |
| width | float | عرض شکل مکان‌گیر جدید. |
| height | float | ارتفاع شکل مکان‌گیر جدید. |

**بازگشت:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شده [IAutoShape](../../com.aspose.slides/iautoshape) با یک مکان‌گیر محتوا (عمودی).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا محتواهای متنی را در خود نگه دارد.

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


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات X شکل مکان‌گیر جدید. |
| y | float | مختصات Y شکل مکان‌گیر جدید. |
| width | float | عرض شکل مکان‌گیر جدید. |
| height | float | ارتفاع شکل مکان‌گیر جدید. |

**بازگشت:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شده [IAutoShape](../../com.aspose.slides/iautoshape) با یک مکان‌گیر متن.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا محتواهای متنی را به صورت عمودی در خود نگه دارد.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات X شکل مکان‌گیر جدید. |
| y | float | مختصات Y شکل مکان‌گیر جدید. |
| width | float | عرض شکل مکان‌گیر جدید. |
| height | float | ارتفاع شکل مکان‌گیر جدید. |

**بازگشت:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شده [IAutoShape](../../com.aspose.slides/iautoshape) با یک مکان‌گیر متن (عمودی).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا یک تصویر را در خود نگه دارد.

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


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات X شکل مکان‌گیر جدید. |
| y | float | مختصات Y شکل مکان‌گیر جدید. |
| width | float | عرض شکل مکان‌گیر جدید. |
| height | float | ارتفاع شکل مکان‌گیر جدید. |

**بازگشت:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شده [IAutoShape](../../com.aspose.slides/iautoshape) با یک مکان‌گیر تصویر.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا یک نمودار را در خود نگه دارد.

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


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات X شکل مکان‌گیر جدید. |
| y | float | مختصات Y شکل مکان‌گیر جدید. |
| width | float | عرض شکل مکان‌گیر جدید. |
| height | float | ارتفاع شکل مکان‌گیر جدید. |

**بازگشت:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شده [IAutoShape](../../com.aspose.slides/iautoshape) با یک مکان‌گیر نمودار.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا یک جدول را در خود نگه دارد.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات X شکل مکان‌گیر جدید. |
| y | float | مختصات Y شکل مکان‌گیر جدید. |
| width | float | عرض شکل مکان‌گیر جدید. |
| height | float | ارتفاع شکل مکان‌گیر جدید. |

**بازگشت:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شده [IAutoShape](../../com.aspose.slides/iautoshape) با یک مکان‌گیر جدول.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا یک نمودار SmartArt را در خود نگه دارد.

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


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات X شکل مکان‌گیر جدید. |
| y | float | مختصات Y شکل مکان‌گیر جدید. |
| width | float | عرض شکل مکان‌گیر جدید. |
| height | float | ارتفاع شکل مکان‌گیر جدید. |

**بازگشت:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شده [IAutoShape](../../com.aspose.slides/iautoshape) با یک مکان‌گیر SmartArt.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا یک شی رسانه‌ای را در خود نگه دارد.

--------------------

> ```
> مثال زیر نشان می‌دهد که چگونه شکل مکان‌گیر Media را به اسلاید طرح‌بندی اضافه کنید.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات X شکل مکان‌گیر جدید. |
| y | float | مختصات Y شکل مکان‌گیر جدید. |
| width | float | عرض شکل مکان‌گیر جدید. |
| height | float | ارتفاع شکل مکان‌گیر جدید. |

**بازگشت:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شده [IAutoShape](../../com.aspose.slides/iautoshape) با یک مکان‌گیر رسانه.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

یک شکل مکان‌گیر جدید به اسلاید طرح‌بندی اضافه می‌کند تا یک تصویر آنلاین را در خود نگه دارد.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات X شکل مکان‌گیر جدید. |
| y | float | مختصات Y شکل مکان‌گیر جدید. |
| width | float | عرض شکل مکان‌گیر جدید. |
| height | float | ارتفاع شکل مکان‌گیر جدید. |

**بازگشت:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شده [IAutoShape](../../com.aspose.slides/iautoshape) با یک مکان‌گیر تصویر آنلاین.