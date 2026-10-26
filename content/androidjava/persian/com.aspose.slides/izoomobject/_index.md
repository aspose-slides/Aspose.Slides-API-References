---
title: IZoomObject
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک شیء Zoom را در یک اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/izoomobject/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

یک شیء Zoom را در یک اسلاید نشان می‌دهد.

## متدها

| Method | Description |
| --- | --- |
| [getImageType()](#getImageType--) | دریافت یا تنظیم نوع تصویر یک شیء Zoom. |
| [setImageType(int value)](#setImageType-int-) | دریافت یا تنظیم نوع تصویر یک شیء Zoom. |
| [getReturnToParent()](#getReturnToParent--) | دریافت یا تنظیم رفتار ناوبری در اسلایدشو. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | دریافت یا تنظیم رفتار ناوبری در اسلایدشو. |
| [getShowBackground()](#getShowBackground--) | دریافت یا تنظیم مقداری که تعیین می‌کند آیا Zoom پس‌زمینه اسلاید مقصد را استفاده می‌کند یا خیر. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | دریافت یا تنظیم مقداری که تعیین می‌کند آیا Zoom پس‌زمینه اسلاید مقصد را استفاده می‌کند یا خیر. |
| [getZoomImage()](#getZoomImage--) | دریافت یا تنظیم تصویر برای شیء Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | دریافت یا تنظیم تصویر برای شیء Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | دریافت یا تنظیم مدت زمان انتقال بین Zoom و اسلاید. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | دریافت یا تنظیم مدت زمان انتقال بین Zoom و اسلاید. |

### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

دریافت یا تنظیم نوع تصویر یک شیء Zoom. قابل خواندن/نوشتن [ZoomImageType](../../com.aspose.slides/zoomimagetype). مقدار پیش‌فرض: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

مشخص می‌کند آیا شیء Zoom از پیش‌نمایش اسلاید یا تصویر جلد استفاده می‌کند.

**بازگشت:**
int

### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

دریافت یا تنظیم نوع تصویر یک شیء Zoom. قابل خواندن/نوشتن [ZoomImageType](../../com.aspose.slides/zoomimagetype). مقدار پیش‌فرض: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

مشخص می‌کند آیا شیء Zoom از پیش‌نمایش اسلاید یا تصویر جلد استفاده می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

دریافت یا تنظیم رفتار ناوبری در اسلایدشو. قابل خواندن/نوشتن boolean. مقدار پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

مقدار true این خصوصیت رفتار ناوبری بازگشت به والد در اسلایدشو را مشخص می‌کند.

**بازگشت:**
boolean

### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

دریافت یا تنظیم رفتار ناوبری در اسلایدشو. قابل خواندن/نوشتن boolean. مقدار پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

مقدار true این خصوصیت رفتار ناوبری بازگشت به والد در اسلایدشو را مشخص می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

دریافت یا تنظیم مقداری که تعیین می‌کند آیا Zoom پس‌زمینه اسلاید مقصد را استفاده می‌کند یا خیر. قابل خواندن/نوشتن boolean. مقدار پیش‌فرض: true

--------------------

> ```
> The example demonstrates removing the background of an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**
boolean

### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```

دریافت یا تنظیم مقداری که تعیین می‌کند آیا Zoom پس‌زمینه اسلاید مقصد را استفاده می‌کند یا خیر. قابل خواندن/نوشتن boolean. مقدار پیش‌فرض: true

--------------------

> ```
> The example demonstrates removing the background of an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```

دریافت یا تنظیم تصویر برای شیء Zoom. قابل خواندن/نوشتن [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> مثال نشان می‌دهد که چگونه تصویر یک شیء Zoom را تغییر می‌دهید:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**
[IPPImage](../../com.aspose.slides/ippimage)

### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```

دریافت یا تنظیم تصویر برای شیء Zoom. قابل خواندن/نوشتن [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```

دریافت یا تنظیم مدت زمان انتقال بین Zoom و اسلاید. قابل خواندن/نوشتن float. مقدار پیش‌فرض: 1.0f

--------------------

> ```
> مثال نشان می‌دهد که نحوه تغییر مدت زمان انتقال بین Zoom و اسلاید:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


اگر مشخص نشود (TransitionDur = 0)، از انتقال اسلاید مقصد و زمان‌بندی‌های مربوط به آن انتقال استفاده می‌شود.

**بازگشت:**
float

### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

دریافت یا تنظیم مدت زمان انتقال بین Zoom و اسلاید. قابل خواندن/نوشتن float. مقدار پیش‌فرض: 1.0f

--------------------

> ```
> the example demonstrates changing the duration of the transition between Zoom and slide:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


اگر مشخص نشود (TransitionDur = 0)، از انتقال اسلاید مقصد و زمان‌بندی‌های مربوط به آن انتقال استفاده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |