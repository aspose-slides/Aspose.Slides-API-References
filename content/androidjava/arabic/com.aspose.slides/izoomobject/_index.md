---
title: IZoomObject
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل كائن Zoom في شريحة.
type: docs
url: /ar/com.aspose.slides/izoomobject/
---
**جميع الواجهات التي تم تنفيذها:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

يمثل كائن Zoom في شريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getImageType()](#getImageType--) | يحصل أو يضبط نوع الصورة لكائن Zoom. |
| [setImageType(int value)](#setImageType-int-) | يحصل أو يضبط نوع الصورة لكائن Zoom. |
| [getReturnToParent()](#getReturnToParent--) | يحصل أو يضبط سلوك التنقل في عرض الشرائح. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | يحصل أو يضبط سلوك التنقل في عرض الشرائح. |
| [getShowBackground()](#getShowBackground--) | يحصل أو يضبط القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الوجهة. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | يحصل أو يضبط القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الوجهة. |
| [getZoomImage()](#getZoomImage--) | يحصل أو يضبط الصورة لكائن Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | يحصل أو يضبط الصورة لكائن Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | يحصل أو يضبط مدة الانتقال بين Zoom والشريحة. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | يحصل أو يضبط مدة الانتقال بين Zoom والشريحة. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```


يحصل أو يضبط نوع الصورة لكائن Zoom. قراءة/كتابة [ZoomImageType](../../com.aspose.slides/zoomimagetype). القيمة الافتراضية: Preview

--------------------

> ```
> يظهر هذا المثال تغيير نوع الصورة إلى القيمة Preview. 
>  في هذه الحالة تتغير الصورة الحالية لكائن Zoom إلى صورة الشريحة:
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

تحدد ما إذا كان كائن Zoom يستخدم معاينة الشريحة أو صورة غلاف.

**الإرجاع:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```


يحصل أو يضبط نوع الصورة لكائن Zoom. قراءة/كتابة [ZoomImageType](../../com.aspose.slides/zoomimagetype). القيمة الافتراضية: Preview

--------------------

> ```
> يوضح هذا المثال تغيير نوع الصورة إلى القيمة Preview. 
>  في هذه الحالة تتغير الصورة الحالية لكائن Zoom إلى صورة الشريحة:
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

تحدد ما إذا كان كائن Zoom يستخدم معاينة الشريحة أو صورة غلاف.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```


يحصل أو يضبط سلوك التنقل في عرض الشرائح. قراءة/كتابة boolean. القيمة الافتراضية: false

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

القيمة true للخاصية تشير إلى سلوك العودة إلى العنصر الأصل في عرض الشرائح.

**الإرجاع:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```


يحصل أو يضبط سلوك التنقل في عرض الشرائح. قراءة/كتابة boolean. القيمة الافتراضية: false

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

القيمة true للخاصية تشير إلى سلوك العودة إلى العنصر الأصل في عرض الشرائح.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```


يحصل أو يضبط القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الوجهة. قراءة/كتابة boolean. القيمة الافتراضية: true

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


**الإرجاع:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```


يحصل أو يضبط القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الوجهة. قراءة/كتابة boolean. القيمة الافتراضية: true

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```


يحصل أو يضبط الصورة لكائن Zoom. قراءة/كتابة [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> يوضح المثال تغيير صورة لكائن Zoom:
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

**الإرجاع:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```


يحصل أو يضبط الصورة لكائن Zoom. قراءة/كتابة [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> يوضح المثال تغيير صورة لكائن Zoom:
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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```


يحصل أو يضبط مدة الانتقال بين Zoom والشريحة. قراءة/كتابة float. القيمة الافتراضية: 1.0f

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

إذا لم يتم تحديده (TransitionDur = 0)، سيستخدم انتقال الشريحة الوجهة والتوقيتات المرتبطة بذلك الانتقال.

**الإرجاع:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```


يحصل أو يضبط مدة الانتقال بين Zoom والشريحة. قراءة/كتابة float. القيمة الافتراضية: 1.0f

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

إذا لم يتم تحديده (TransitionDur = 0)، سيستخدم انتقال الشريحة الوجهة والتوقيتات المرتبطة بذلك الانتقال.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |