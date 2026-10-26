---
title: LayoutPlaceholderManager
second_title: مرجع API Aspose.Slides برای جاوا
description: نماینده‌ای است که به شما امکان اضافه‌کردن placeholderها به اسلاید چیدمان را می‌دهد.
type: docs
url: /fa/com.aspose.slides/layoutplaceholdermanager/
---
**ارث‌بری:**  
java.lang.Object

**تمام اینترفیس‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)  
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

نماینده‌ای که به شما اجازه می‌دهد placeholderها را به اسلاید چیدمان اضافه کنید.

## متدها

| متد | توضیح |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا محتوایی مانند تصویر، جدول، رسانه یا متن را در خود نگه دارد. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا محتوایی مانند تصویر، جدول، رسانه یا متن را به صورت عمودی در خود نگه دارد. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا محتوای متنی را در خود نگه دارد. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا محتوای متنی را به صورت عمودی در خود نگه دارد. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا یک تصویر را در خود نگه دارد. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا یک نمودار را در خود نگه دارد. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا یک جدول را در خود نگه دارد. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا یک نمودار SmartArt را در خود نگه دارد. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا یک شیء رسانه‌ای را در خود نگه دارد. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا یک تصویر آنلاین را در خود نگه دارد. |

### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا محتوایی مانند تصویر، جدول، رسانه یا متن را در خود نگه دارد.

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
| x | float | مختصات X شکل placeholder جدید. |
| y | float | مختصات Y شکل placeholder جدید. |
| width | float | عرض شکل placeholder جدید. |
| height | float | ارتفاع شکل placeholder جدید. |

**بازگرداندن:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شد [IAutoShape](../../com.aspose.slides/iautoshape) با یک placeholder محتوا.

### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا محتوایی مانند تصویر، جدول، رسانه یا متن را به صورت عمودی در خود نگه دارد.

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
| x | float | مختصات X شکل placeholder جدید. |
| y | float | مختصات Y شکل placeholder جدید. |
| width | float | عرض شکل placeholder جدید. |
| height | float | ارتفاع شکل placeholder جدید. |

**بازگرداندن:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شد [IAutoShape](../../com.aspose.slides/iautoshape) با یک placeholder محتوا (عمودی).

### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا محتوای متنی را در خود نگه دارد.

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
| x | float | مختصات X شکل placeholder جدید. |
| y | float | مختصات Y شکل placeholder جدید. |
| width | float | عرض شکل placeholder جدید. |
| height | float | ارتفاع شکل placeholder جدید. |

**بازگرداندن:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شد [IAutoShape](../../com.aspose.slides/iautoshape) با یک placeholder متنی.

### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا محتوای متنی را به صورت عمودی در خود نگه دارد.

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه شکل placeholder متن (عمودی) را به اسلاید چیدمان اضافه کنید.
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
| x | float | مختصات X شکل placeholder جدید. |
| y | float | مختصات Y شکل placeholder جدید. |
| width | float | عرض شکل placeholder جدید. |
| height | float | ارتفاع شکل placeholder جدید. |

**بازگرداندن:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شد [IAutoShape](../../com.aspose.slides/iautoshape) با یک placeholder متنی (عمودی).

### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا یک تصویر را در خود نگه دارد.

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه شکل placeholder تصویر را به اسلاید چیدمان اضافه کنید.
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
| x | float | مختصات X شکل placeholder جدید. |
| y | float | مختصات Y شکل placeholder جدید. |
| width | float | عرض شکل placeholder جدید. |
| height | float | ارتفاع شکل placeholder جدید. |

**بازگرداندن:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شد [IAutoShape](../../com.aspose.slides/iautoshape) با یک placeholder تصویر.

### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا یک نمودار را در خود نگه دارد.

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
| x | float | مختصات X شکل placeholder جدید. |
| y | float | مختصات Y شکل placeholder جدید. |
| width | float | عرض شکل placeholder جدید. |
| height | float | ارتفاع شکل placeholder جدید. |

**بازگرداندن:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شد [IAutoShape](../../com.aspose.slides/iautoshape) با یک placeholder نمودار.

### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا یک جدول را در خود نگه دارد.

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
| x | float | مختصات X شکل placeholder جدید. |
| y | float | مختصات Y شکل placeholder جدید. |
| width | float | عرض شکل placeholder جدید. |
| height | float | ارتفاع شکل placeholder جدید. |

**بازگرداندن:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شد [IAutoShape](../../com.aspose.slides/iautoshape) با یک placeholder جدول.

### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا یک نمودار SmartArt را در خود نگه دارد.

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه شکل placeholder SmartArt را به اسلاید چیدمان اضافه کنید.
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
| x | float | مختصات X شکل placeholder جدید. |
| y | float | مختصات Y شکل placeholder جدید. |
| width | float | عرض شکل placeholder جدید. |
| height | float | ارتفاع شکل placeholder جدید. |

**بازگرداندن:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شد [IAutoShape](../../com.aspose.slides/iautoshape) با یک placeholder SmartArt.

### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا یک شیء رسانه‌ای را در خود نگه دارد.

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه شکل placeholder Media را به اسلاید چیدمان اضافه کنید.
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
| x | float | مختصات X شکل placeholder جدید. |
| y | float | مختصات Y شکل placeholder جدید. |
| width | float | عرض شکل placeholder جدید. |
| height | float | ارتفاع شکل placeholder جدید. |

**بازگرداندن:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شد [IAutoShape](../../com.aspose.slides/iautoshape) با یک placeholder رسانه.

### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

یک شکل placeholder جدید به اسلاید چیدمان اضافه می‌کند تا یک تصویر آنلاین را در خود نگه دارد.

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه شکل placeholder تصویر آنلاین را به اسلاید چیدمان اضافه کنید.
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
| x | float | مختصات X شکل placeholder جدید. |
| y | float | مختصات Y شکل placeholder جدید. |
| width | float | عرض شکل placeholder جدید. |
| height | float | ارتفاع شکل placeholder جدید. |

**بازگرداندن:**
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد شد [IAutoShape](../../com.aspose.slides/iautoshape) با یک placeholder تصویر آنلاین.