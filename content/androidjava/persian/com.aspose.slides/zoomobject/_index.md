---
title: ZoomObject
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک شی Zoom را در یک اسلاید نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/zoomobject/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

یک شی Zoom را در یک اسلاید نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getImageType()](#getImageType--) | دریافت یا تنظیم نوع تصویر شی Zoom. |
| [setImageType(int value)](#setImageType-int-) | دریافت یا تنظیم نوع تصویر شی Zoom. |
| [getReturnToParent()](#getReturnToParent--) | دریافت یا تنظیم رفتار ناوبری در اسلایدشو. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | دریافت یا تنظیم رفتار ناوبری در اسلایدشو. |
| [getShowBackground()](#getShowBackground--) | دریافت یا تنظیم مقداری که تعیین می‌کند آیا Zoom از پس‌زمینه اسلاید مقصد استفاده می‌کند یا خیر. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | دریافت یا تنظیم مقداری که تعیین می‌کند آیا Zoom از پس‌زمینه اسلاید مقصد استفاده می‌کند یا خیر. |
| [getZoomImage()](#getZoomImage--) | دریافت یا تنظیم تصویر برای شی Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | دریافت یا تنظیم تصویر برای شی Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | دریافت یا تنظیم مدت زمان انتقال بین Zoom و اسلاید. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | دریافت یا تنظیم مدت زمان انتقال بین Zoom و اسلاید. |
### getImageType() {#getImageType--}
```
public final int getImageType()
```

دریافت یا تنظیم نوع تصویر یک شی Zoom. خواندنی/نوشتنی [ZoomImageType](../../com.aspose.slides/zoomimagetype). مقدار پیش‌فرض: Preview

--------------------

> ```
> مثال بعدی تغییر نوع تصویر به مقدار Preview را نشان می‌دهد. 
>  در این حالت تصویر فعلی یک شی Zoom به تصویر اسلاید تغییر می‌کند:
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

مشخص می‌کند که آیا شی Zoom از پیش‌نمایش اسلاید یا تصویر کاور استفاده می‌کند.

**بازگشت:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

دریافت یا تنظیم نوع تصویر یک شی Zoom. خواندنی/نوشتنی [ZoomImageType](../../com.aspose.slides/zoomimagetype). مقدار پیش‌فرض: Preview

--------------------

> ```
> مثال بعدی تغییر نوع تصویر به مقدار Preview را نشان می‌دهد. 
>  در این حالت تصویر فعلی یک شی Zoom به تصویر اسلاید تغییر می‌کند:
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

مشخص می‌کند که آیا شی Zoom از پیش‌نمایش اسلاید یا تصویر کاور استفاده می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

دریافت یا تنظیم رفتار ناوبری در اسلایدشو. خواندنی/نوشتنی boolean. مقدار پیش‌فرض: false

--------------------

> ```
> مثال:
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

مقدار true این ویژگی رفتار بازگشت به والد در اسلایدشو را مشخص می‌کند.

**بازگشت:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

دریافت یا تنظیم رفتار ناوبری در اسلایدشو. خواندنی/نوشتنی boolean. مقدار پیش‌فرض: false

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

مقدار true این ویژگی رفتار بازگشت به والد در اسلایدشو را مشخص می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

دریافت یا تنظیم مقداری که تعیین می‌کند آیا Zoom از پس‌زمینه اسلاید مقصد استفاده می‌کند یا خیر. خواندنی/نوشتنی boolean. مقدار پیش‌فرض: true

--------------------

> ```
> the example demonstrates removing the background of an image of a Zoom object:
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
public final void setShowBackground(boolean value)
```

دریافت یا تنظیم مقداری که تعیین می‌کند آیا Zoom از پس‌زمینه اسلاید مقصد استفاده می‌کند یا خیر. خواندنی/نوشتنی boolean. مقدار پیش‌فرض: true

--------------------

> ```
> مثال زیر حذف پس‌زمینه تصویر یک شی Zoom را نشان می‌دهد:
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
public final IPPImage getZoomImage()
```

دریافت یا تنظیم تصویر برای شی Zoom. خواندنی/نوشتنی [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> مثال زیر تغییر تصویر یک شی Zoom را نشان می‌دهد:
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
public final void setZoomImage(IPPImage value)
```

دریافت یا تنظیم تصویر برای شی Zoom. خواندنی/نوشتنی [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> مثال زیر تغییر تصویر یک شی Zoom را نشان می‌دهد:
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
public final float getTransitionDuration()
```

دریافت یا تنظیم مدت زمان انتقال بین Zoom و اسلاید. خواندنی/نوشتنی float. مقدار پیش‌فرض: 1.0f

--------------------

> ```
> مثال زیر تغییر مدت زمان انتقال بین Zoom و اسلاید را نشان می‌دهد:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


اگر مشخص نشود (TransitionDur = 0)، انتقال اسلاید مقصد و زمان‌بندی‌های مربوط به آن استفاده خواهد شد.

**بازگشت:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

دریافت یا تنظیم مدت زمان انتقال بین Zoom و اسلاید. خواندنی/نوشتنی float. مقدار پیش‌فرض: 1.0f

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

اگر مشخص نشود (TransitionDur = 0)، انتقال اسلاید مقصد و زمان‌بندی‌های مربوط به آن استفاده خواهد شد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |