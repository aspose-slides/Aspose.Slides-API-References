---
title: ZoomObject
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایش یک شی Zoom در یک اسلاید.
type: docs
url: /fa/com.aspose.slides/zoomobject/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**تمام اینترفیس‌های پیاده‌سازی شده:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

نمایش یک شی Zoom در یک اسلاید.
## متدها

| متد | توضیح |
| --- | --- |
| [getImageType()](#getImageType--) | دریافت یا تنظیم نوع تصویر یک شی Zoom. |
| [setImageType(int value)](#setImageType-int-) | دریافت یا تنظیم نوع تصویر یک شی Zoom. |
| [getReturnToParent()](#getReturnToParent--) | دریافت یا تنظیم رفتار ناوبری در اسلایدشو. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | دریافت یا تنظیم رفتار ناوبری در اسلایدشو. |
| [getShowBackground()](#getShowBackground--) | دریافت یا تنظیم مقداری که مشخص می‌کند آیا Zoom از پس‌زمینه اسلاید مقصد استفاده می‌کند. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | دریافت یا تنظیم مقداری که مشخص می‌کند آیا Zoom از پس‌زمینه اسلاید مقصد استفاده می‌کند. |
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
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مشخص می‌کند که آیا شی Zoom از پیش‌نمایش اسلاید یا تصویر جلد استفاده می‌کند.

**بازگشت:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```


دریافت یا تنظیم نوع تصویر یک شی Zoom. خواندنی/نوشتنی [ZoomImageType](../../com.aspose.slides/zoomimagetype). مقدار پیش‌فرض: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مشخص می‌کند که آیا شی Zoom از پیش‌نمایش اسلاید یا تصویر جلد استفاده می‌کند.

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

مقدار true این ویژگی رفتار ناوبری بازگشت به والد را در اسلایدشو مشخص می‌کند.

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

مقدار true این ویژگی رفتار ناوبری بازگشت به والد را در اسلایدشو مشخص می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```


دریافت یا تنظیم مقداری که مشخص می‌کند آیا Zoom از پس‌زمینه اسلاید مقصد استفاده می‌کند. خواندنی/نوشتنی boolean. مقدار پیش‌فرض: true

--------------------

> ```
> این مثال حذف پس‌زمینه تصویر یک شی Zoom را نشان می‌دهد:
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


دریافت یا تنظیم مقداری که مشخص می‌کند آیا Zoom از پس‌زمینه اسلاید مقصد استفاده می‌کند. خواندنی/نوشتنی boolean. مقدار پیش‌فرض: true

--------------------

> ```
> این مثال حذف پس‌زمینه تصویر یک شی Zoom را نشان می‌دهد:
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
> این مثال تغییر تصویر یک شی Zoom را نشان می‌دهد:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
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
> این مثال تغییر تصویر یک شی Zoom را نشان می‌دهد:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
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
> این مثال تغییر مدت زمان انتقال بین Zoom و اسلاید را نشان می‌دهد:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

اگر مشخص نشود (TransitionDur = 0)، از انتقال اسلاید مقصد و زمان‌بندی‌های مربوط به آن استفاده خواهد شد.

**بازگشت:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```


دریافت یا تنظیم مدت زمان انتقال بین Zoom و اسلاید. خواندنی/نوشتنی float. مقدار پیش‌فرض: 1.0f

--------------------

> ```
> این مثال تغییر مدت زمان انتقال بین Zoom و اسلاید را نشان می‌دهد:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

اگر مشخص نشود (TransitionDur = 0)، از انتقال اسلاید مقصد و زمان‌بندی‌های مربوط به آن استفاده خواهد شد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |