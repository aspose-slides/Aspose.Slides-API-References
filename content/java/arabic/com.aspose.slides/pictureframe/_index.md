---
title: PictureFrame
second_title: Aspose.Slides لمرجع API لجافا
description: يمثل إطارًا يحتوي على صورة بداخله.
type: docs
url: /ar/com.aspose.slides/pictureframe/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**كل الواجهات المنفذة:**  
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)  
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

يمثل إطارًا يحتوي على صورة بالداخل.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // يضيف إطار صوت إلى الشريحة مع موضع وحجم محددين.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // يضيف صورة إلى موارد العرض التقديمي.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // يحدد الصورة لإطار الصوت.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //يحفظ العرض التقديمي المعدل إلى القرص
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | إرجاع أقفال shape. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | إرجاع كائن PictureFillFormat لإطار صورة. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | إرجاع أو تعيين مقياس الارتفاع (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | إرجاع أو تعيين مقياس الارتفاع (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | إرجاع أو تعيين مقياس العرض (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | إرجاع أو تعيين مقياس العرض (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. |
| [isCameo()](#isCameo--) | تحديد ما إذا كان PictureFrame كائن Cameo أم لا. |

### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```

إرجاع أقفال shape. قراءة فقط [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**الإرجاع:**  
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

إرجاع أو تعيين نوع AutoShape لإطار PictureFrame. هناك جميع العناصر المسموح بها في المجموعة [ShapeType](../../com.aspose.slides/shapetype)، باستثناء جميع أنواع الخطوط:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5.

قراءة/كتابة [ShapeType](../../com.aspose.slides/shapetype).

**الإرجاع:**  
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

إرجاع أو تعيين نوع AutoShape لإطار PictureFrame. هناك جميع العناصر المسموح بها في المجموعة [ShapeType](../../com.aspose.slides/shapetype)، باستثناء جميع أنواع الخطوط:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5.

قراءة/كتابة [ShapeType](../../com.aspose.slides/shapetype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```

إرجاع كائن PictureFillFormat لإطار صورة. قراءة فقط [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**الإرجاع:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```

إرجاع أو تعيين مقياس الارتفاع (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. قراءة/كتابة  float .

**الإرجاع:**  
float

### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```

إرجاع أو تعيين مقياس الارتفاع (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```

إرجاع أو تعيين مقياس العرض (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. قراءة/كتابة  float .

**الإرجاع:**  
float

### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```

إرجاع أو تعيين مقياس العرض (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. قراءة/كتابة  float .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```

تحديد ما إذا كان PictureFrame كائن Cameo أم لا. منطقي قراءة فقط.

**الإرجاع:**  
boolean