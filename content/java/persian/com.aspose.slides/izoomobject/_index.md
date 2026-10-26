---
title: IZoomObject
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایش یک شی Zoom در یک اسلاید.
type: docs
url: /fa/com.aspose.slides/izoomobject/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

نمایش یک شی Zoom در یک اسلاید.
## Methods

| Method | Description |
| --- | --- |
| [getImageType()](#getImageType--) | Gets or sets the image type of a zoom object. |
| [setImageType(int value)](#setImageType-int-) | Gets or sets the image type of a zoom object. |
| [getReturnToParent()](#getReturnToParent--) | Gets or sets the navigation behavior in slideshow. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Gets or sets the navigation behavior in slideshow. |
| [getShowBackground()](#getShowBackground--) | Gets or sets value that specifies whether the Zoom will use the background of the destination slide. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Gets or sets value that specifies whether the Zoom will use the background of the destination slide. |
| [getZoomImage()](#getZoomImage--) | Gets or sets image for zoom object. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Gets or sets image for zoom object. |
| [getTransitionDuration()](#getTransitionDuration--) | Gets or sets the duration of the transition between Zoom and slide. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Gets or sets the duration of the transition between Zoom and slide. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

دریافت یا تنظیم نوع تصویر یک شی Zoom. قابل خواندن/قابل نوشتن [ZoomImageType](../../com.aspose.slides/zoomimagetype). مقدار پیش‌فرض: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

مشخص می‌کند که آیا شی Zoom از پیش‌نمایش اسلاید یا تصویر پوشش استفاده می‌کند.

**Returns:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

دریافت یا تنظیم نوع تصویر یک شی Zoom. قابل خواندن/قابل نوشتن [ZoomImageType](../../com.aspose.slides/zoomimagetype). مقدار پیش‌فرض: Preview

--------------------

> ```
> این مثال نحوه تغییر Image Type به مقدار Preview را نشان می‌دهد. 
>  در این حالت تصویر فعلی یک شی Zoom به تصویر اسلاید تغییر می‌کند:
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

مشخص می‌کند که آیا شی Zoom از پیش‌نمایش اسلاید یا تصویر پوشش استفاده می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

دریافت یا تنظیم رفتار ناوبری در حالت اسلایدشو. قابل خواندن/قابل نوشتن boolean. مقدار پیش‌فرض: false

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

مقدار true این ویژگی رفتار ناوبری بازگشت به والد را در اسلایدشو مشخص می‌کند.

**Returns:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

دریافت یا تنظیم رفتار ناوبری در حالت اسلایدشو. قابل خواندن/قابل نوشتن boolean. مقدار پیش‌فرض: false

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

مقدار true این ویژگی رفتار ناوبری بازگشت به والد را در اسلایدشو مشخص می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

دریافت یا تنظیم مقداری که مشخص می‌کند آیا Zoom پس‌زمینه اسلاید مقصد را استفاده می‌کند. قابل خواندن/قابل نوشتن boolean. مقدار پیش‌فرض: true

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


**Returns:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```

دریافت یا تنظیم مقداری که مشخص می‌کند آیا Zoom پس‌زمینه اسلاید مقصد را استفاده می‌کند. قابل خواندن/قابل نوشتن boolean. مقدار پیش‌فرض: true

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


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```

دریافت یا تنظیم تصویر برای شی Zoom. قابل خواندن/قابل نوشتن [IPPImage](../../com.aspose.slides/ippimage).

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

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```

دریافت یا تنظیم تصویر برای شی Zoom. قابل خواندن/قابل نوشتن [IPPImage](../../com.aspose.slides/ippimage).

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


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```

دریافت یا تنظیم مدت زمان انتقال بین Zoom و اسلاید. قابل خواندن/قابل نوشتن float. مقدار پیش‌فرض: 1.0f

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

اگر مقدار مشخص نشود (TransitionDur = 0)، از انتقال اسلاید مقصد و زمان‌بندی‌های مربوط به آن استفاده می‌کند.

**Returns:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

دریافت یا تنظیم مدت زمان انتقال بین Zoom و اسلاید. قابل خواندن/قابل نوشتن float. مقدار پیش‌فرض: 1.0f

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

اگر مقدار مشخص نشود (TransitionDur = 0)، از انتقال اسلاید مقصد و زمان‌بندی‌های مربوط به آن استفاده می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |