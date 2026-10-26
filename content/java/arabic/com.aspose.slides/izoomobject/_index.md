---
title: IZoomObject
second_title: Aspose.Slides لمرجع API لجافا
description: يمثل كائن Zoom في شريحة.
type: docs
url: /ar/com.aspose.slides/izoomobject/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

يمثل كائن Zoom في الشريحة.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getImageType()](#getImageType--) | يُحصل على أو يُعيّن نوع الصورة لكائن Zoom. |
| [setImageType(int value)](#setImageType-int-) | يُحصل على أو يُعيّن نوع الصورة لكائن Zoom. |
| [getReturnToParent()](#getReturnToParent--) | يُحصل على أو يُعيّن سلوك التنقل في عرض الشرائح. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | يُحصل على أو يُعيّن سلوك التنقل في عرض الشرائح. |
| [getShowBackground()](#getShowBackground--) | يُحصل على أو يُعيّن القيمة التي تحدد ما إذا كان Zoom سيستخدم الخلفية للشريحة المستهدفة. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | يُحصل على أو يُعيّن القيمة التي تحدد ما إذا كان Zoom سيستخدم الخلفية للشريحة المستهدفة. |
| [getZoomImage()](#getZoomImage--) | يُحصل على أو يُعيّن الصورة لكائن Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | يُحصل على أو يُعيّن الصورة لكائن Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | يُحصل على أو يُعيّن مدة الانتقال بين Zoom والشريحة. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | يُحصل على أو يُعيّن مدة الانتقال بين Zoom والشريحة. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

يُحصل على أو يُعيّن نوع الصورة لكائن Zoom. قراءة/كتابة [ZoomImageType](../../com.aspose.slides/zoomimagetype). القيمة الافتراضية: Preview

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

يحدد ما إذا كان كائن Zoom يستخدم معاينة الشريحة أو صورة غلاف.

**القيمة المرجعة:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

يُحصل على أو يُعيّن نوع الصورة لكائن Zoom. قراءة/كتابة [ZoomImageType](../../com.aspose.slides/zoomimagetype). القيمة الافتراضية: Preview

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

يحدد ما إذا كان كائن Zoom يستخدم معاينة الشريحة أو صورة غلاف.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

يُحصل على أو يُعيّن سلوك التنقل في عرض الشرائح. قراءة/كتابة boolean. القيمة الافتراضية: false

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

القيمة true الخاصية تحدد سلوك العودة إلى السلف في عرض الشرائح.

**القيمة المرجعة:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

يُحصل على أو يُعيّن سلوك التنقل في عرض الشرائح. قراءة/كتابة boolean. القيمة الافتراضية: false

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

القيمة true الخاصية تحدد سلوك العودة إلى السلف في عرض الشرائح.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

يُحصل على أو يُعيّن القيمة التي تحدد ما إذا كان Zoom سيستخدم الخلفية للشريحة المستهدفة. قراءة/كتابة boolean. القيمة الافتراضية: true

--------------------

> ```
> يوضح المثال إزالة خلفية صورة كائن Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```

يُحصل على أو يُعيّن القيمة التي تحدد ما إذا كان Zoom سيستخدم الخلفية للشريحة المستهدفة. قراءة/كتابة boolean. القيمة الافتراضية: true

--------------------

> ```
> يوضح المثال إزالة خلفية صورة كائن Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```

يُحصل على أو يُعيّن الصورة لكائن Zoom. قراءة/كتابة [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
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


**القيمة المرجعة:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```

يُحصل على أو يُعيّن الصورة لكائن Zoom. قراءة/كتابة [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```

يُحصل على أو يُعيّن مدة الانتقال بين Zoom والشريحة. قراءة/كتابة float. القيمة الافتراضية: 1.0f

--------------------

> ```
> يوضح المثال تغيير مدة الانتقال بين Zoom والشريحة:
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

إذا لم يُحدَّد (TransitionDur = 0)، سيُستخدم انتقال الشريحة المستهدفة والتوقيتات المرتبطة بذلك الانتقال.

**القيمة المرجعة:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

يُحصل على أو يُعيّن مدة الانتقال بين Zoom والشريحة. قراءة/كتابة float. القيمة الافتراضية: 1.0f

--------------------

> ```
> يوضح المثال تغيير مدة الانتقال بين Zoom والشريحة:
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

إذا لم يُحدَّد (TransitionDur = 0)، سيُستخدم انتقال الشريحة المستهدفة والتوقيتات المرتبطة بذلك الانتقال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |