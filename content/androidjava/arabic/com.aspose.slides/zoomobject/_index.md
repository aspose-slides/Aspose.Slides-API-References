---
title: ZoomObject
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل كائن Zoom في شريحة.
type: docs
url: /ar/com.aspose.slides/zoomobject/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)  
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

يمثل كائن Zoom في شريحة.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getImageType()](#getImageType--) | الحصول على أو تعيين نوع الصورة لكائن Zoom. |
| [setImageType(int value)](#setImageType-int-) | الحصول على أو تعيين نوع الصورة لكائن Zoom. |
| [getReturnToParent()](#getReturnToParent--) | الحصول على أو تعيين سلوك التنقل في عرض الشرائح. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | الحصول على أو تعيين سلوك التنقل في عرض الشرائح. |
| [getShowBackground()](#getShowBackground--) | الحصول على أو تعيين القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الهدف. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | الحصول على أو تعيين القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الهدف. |
| [getZoomImage()](#getZoomImage--) | الحصول على أو تعيين الصورة لكائن Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | الحصول على أو تعيين الصورة لكائن Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | الحصول على أو تعيين مدة الانتقال بين Zoom والشريحة. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | الحصول على أو تعيين مدة الانتقال بين Zoom والشريحة. |

### getImageType() {#getImageType--}
```
public final int getImageType()
```

الحصول على أو تعيين نوع الصورة لكائن Zoom. قراءة/كتابة [ZoomImageType](../../com.aspose.slides/zoomimagetype). القيمة الافتراضية: Preview

--------------------

> ```
> المثال التالي يوضح تغيير نوع الصورة إلى القيمة Preview. 
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

يحدد ما إذا كان كائن Zoom يستخدم معاينة الشريحة أو صورة الغلاف.

**القيمة المرجعة:**  
int

### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

الحصول على أو تعيين نوع الصورة لكائن Zoom. قراءة/كتابة [ZoomImageType](../../com.aspose.slides/zoomimagetype). القيمة الافتراضية: Preview

--------------------

> ```
> المثال التالي يوضح تغيير نوع الصورة إلى القيمة Preview. 
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

يحدد ما إذا كان كائن Zoom يستخدم معاينة الشريحة أو صورة الغلاف.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

الحصول على أو تعيين سلوك التنقل في عرض الشرائح. قراءة/كتابة boolean. القيمة الافتراضية: false

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

القيمة True للخاصية تحدد سلوك العودة إلى العنصر الأصلي في عرض الشرائح.

**القيمة المرجعة:**  
boolean

### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

الحصول على أو تعيين سلوك التنقل في عرض الشرائح. قراءة/كتابة boolean. القيمة الافتراضية: false

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

القيمة True للخاصية تحدد سلوك العودة إلى العنصر الأصلي في عرض الشرائح.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

الحصول على أو تعيين القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الهدف. قراءة/كتابة boolean. القيمة الافتراضية: true

--------------------

> ```
> المثال يوضح إزالة خلفية صورة كائن Zoom:
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
public final void setShowBackground(boolean value)
```

الحصول على أو تعيين القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الهدف. قراءة/كتابة boolean. القيمة الافتراضية: true

--------------------

> ```
> المثال يوضح إزالة خلفية صورة كائن Zoom:
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
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```

الحصول على أو تعيين الصورة لكائن Zoom. قراءة/كتابة [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> المثال يوضح تغيير صورة لكائن Zoom:
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

**القيمة المرجعة:**  
[IPPImage](../../com.aspose.slides/ippimage)

### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```

الحصول على أو تعيين الصورة لكائن Zoom. قراءة/كتابة [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> المثال يوضح تغيير صورة لكائن Zoom:
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


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
```

الحصول على أو تعيين مدة الانتقال بين Zoom والشريحة. قراءة/كتابة float. القيمة الافتراضية: 1.0f

--------------------

> ```
> المثال يوضح تغيير مدة الانتقال بين Zoom والشريحة:
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

إذا لم يتم تحديده (TransitionDur = 0)، سيتم استخدام انتقال الشريحة الهدف والتوقيتات المرتبطة بهذا الانتقال.

**القيمة المرجعة:**  
float

### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

الحصول على أو تعيين مدة الانتقال بين Zoom والشريحة. قراءة/كتابة float. القيمة الافتراضية: 1.0f

--------------------

> ```
> المثال يوضح تغيير مدة الانتقال بين Zoom والشريحة:
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

إذا لم يتم تحديده (TransitionDur = 0)، سيتم استخدام انتقال الشريحة الهدف والتوقيتات المرتبطة بهذا الانتقال.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |