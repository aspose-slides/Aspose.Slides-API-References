---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Android via Java API Reference
description: نمایندهٔ مدیری است که به شما اجازه می‌دهد جای‌گیرها را به اسلاید قالب اضافه کنید.
type: docs
url: /fa/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

نمایندهٔ مدیری است که به شما اجازه می‌دهد جای‌گیرها را به اسلاید قالب اضافه کنید.

## متدها

| Method | Description |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا محتوایی مانند تصویر، جدول، رسانه یا متن را در بر گیرد. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا محتوایی مانند تصویر، جدول، رسانه یا متن را در جهت عمودی در بر گیرد. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا محتوای متنی را در بر گیرد. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا محتوای متنی را در جهت عمودی در بر گیرد. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا یک تصویر را در بر گیرد. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا یک نمودار را در بر گیرد. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا یک جدول را در بر گیرد. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا یک نمودار SmartArt را در بر گیرد. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا یک شی رسانه‌ای را در بر گیرد. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا یک تصویر آنلاین را در بر گیرد. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا محتوایی مانند تصویر، جدول، رسانه یا متن را در بر گیرد.

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


**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X شکل جای‌گیر جدید. |
| y | float | مختصات Y شکل جای‌گیر جدید. |
| width | float | عرض شکل جای‌گیر جدید. |
| height | float | ارتفاع شکل جای‌گیر جدید. |

**بازگشت:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد [IAutoShape](../../com.aspose.slides/iautoshape) با یک جای‌گیر محتوا.  

### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا محتوایی مانند تصویر، جدول، رسانه یا متن را در جهت عمودی در بر گیرد.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X شکل جای‌گیر جدید. |
| y | float | مختصات Y شکل جای‌گیر جدید. |
| width | float | عرض شکل جای‌گیر جدید. |
| height | float | ارتفاع شکل جای‌گیر جدید. |

**بازگشت:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد [IAutoShape](../../com.aspose.slides/iautoshape) با یک جای‌گیر محتوا (عمودی).  

### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا محتوای متنی را در بر گیرد.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X شکل جای‌گیر جدید. |
| y | float | مختصات Y شکل جای‌گیر جدید. |
| width | float | عرض شکل جای‌گیر جدید. |
| height | float | ارتفاع شکل جای‌گیر جدید. |

**بازگشت:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد [IAutoShape](../../com.aspose.slides/iautoshape) با یک جای‌گیر متن.  

### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا محتوای متنی را در جهت عمودی در بر گیرد.

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


**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X شکل جای‌گیر جدید. |
| y | float | مختصات Y شکل جای‌گیر جدید. |
| width | float | عرض شکل جای‌گیر جدید. |
| height | float | ارتفاع شکل جای‌گیر جدید. |

**بازگشت:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد [IAutoShape](../../com.aspose.slides/iautoshape) با یک جای‌گیر متن (عمودی).  

### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا یک تصویر را در بر گیرد.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X شکل جای‌گیر جدید. |
| y | float | مختصات Y شکل جای‌گیر جدید. |
| width | float | عرض شکل جای‌گیر جدید. |
| height | float | ارتفاع شکل جای‌گیر جدید. |

**بازگشت:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد [IAutoShape](../../com.aspose.slides/iautoshape) با یک جای‌گیر تصویر.  

### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا یک نمودار را در بر گیرد.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X شکل جای‌گیر جدید. |
| y | float | مختصات Y شکل جای‌گیر جدید. |
| width | float | عرض شکل جای‌گیر جدید. |
| height | float | ارتفاع شکل جای‌گیر جدید. |

**بازگشت:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد [IAutoShape](../../com.aspose.slides/iautoshape) با یک جای‌گیر نمودار.  

### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا یک جدول را در بر گیرد.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X شکل جای‌گیر جدید. |
| y | float | مختصات Y شکل جای‌گیر جدید. |
| width | float | عرض شکل جای‌گیر جدید. |
| height | float | ارتفاع شکل جای‌گیر جدید. |

**بازگشت:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد [IAutoShape](../../com.aspose.slides/iautoshape) با یک جای‌گیر جدول.  

### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا یک نمودار SmartArt را در بر گیرد.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X شکل جای‌گیر جدید. |
| y | float | مختصات Y شکل جای‌گیر جدید. |
| width | float | عرض شکل جای‌گیر جدید. |
| height | float | ارتفاع شکل جای‌گیر جدید. |

**بازگشت:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد [IAutoShape](../../com.aspose.slides/iautoshape) با یک جای‌گیر SmartArt.  

### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا یک شی رسانه‌ای را در بر گیرد.

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


**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X شکل جای‌گیر جدید. |
| y | float | مختصات Y شکل جای‌گیر جدید. |
| width | float | عرض شکل جای‌گیر جدید. |
| height | float | ارتفاع شکل جای‌گیر جدید. |

**بازگشت:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد [IAutoShape](../../com.aspose.slides/iautoshape) با یک جای‌گیر رسانه‌ای.  

### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

یک شکل جای‌گیر جدید به اسلاید طرح اضافه می‌کند تا یک تصویر آنلاین را در بر گیرد.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X شکل جای‌گیر جدید. |
| y | float | مختصات Y شکل جای‌گیر جدید. |
| width | float | عرض شکل جای‌گیر جدید. |
| height | float | ارتفاع شکل جای‌گیر جدید. |

**بازگشت:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - ایجاد [IAutoShape](../../com.aspose.slides/iautoshape) با یک جای‌گیر تصویر آنلاین.