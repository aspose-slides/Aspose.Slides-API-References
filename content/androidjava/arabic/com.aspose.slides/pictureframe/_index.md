---
title: PictureFrame
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل إطارًا يحتوي على صورة بداخله.
type: docs
url: /ar/com.aspose.slides/pictureframe/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**جميع الواجهات المُطبقة:**  
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)  
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

يمثل إطارًا يحتوي على صورة بداخله.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // يضيف إطار صوت إلى الشريحة بموقع وحجم محددين.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // يضيف صورة إلى موارد العرض.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // يحدد الصورة لإطار الصوت.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //يحفظ العرض المعدل إلى القرص
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | إرجاع أقفال الشكل. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | إرجاع كائن PictureFillFormat لإطار الصورة. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | إرجاع أو تعيين مقياس الارتفاع (نسبيًا إلى حجم الصورة الأصلي) لإطار الصورة. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | إرجاع أو تعيين مقياس الارتفاع (نسبيًا إلى حجم الصورة الأصلي) لإطار الصورة. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | إرجاع أو تعيين مقياس العرض (نسبيًا إلى حجم الصورة الأصلي) لإطار الصورة. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | إرجاع أو تعيين مقياس العرض (نسبيًا إلى حجم الصورة الأصلي) لإطار الصورة. |
| [isCameo()](#isCameo--) | تحديد ما إذا كان PictureFrame كائن Cameo أم لا. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```

إرجاع أقفال الشكل. للقراءة فقط [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**القيمة المرجعة:**  
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

إرجاع أو تعيين نوع AutoShape لإطار صورة. هناك جميع العناصر المسموح بها في المجموعة [ShapeType](../../com.aspose.slides/shapetype)، باستثناء جميع أنواع الخطوط:

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

للقراءة والكتابة [ShapeType](../../com.aspose.slides/shapetype).

**القيمة المرجعة:**  
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

إرجاع أو تعيين نوع AutoShape لإطار صورة. هناك جميع العناصر المسموح بها في المجموعة [ShapeType](../../com.aspose.slides/shapetype)، باستثناء جميع أنواع الخطوط:

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

للقراءة والكتابة [ShapeType](../../com.aspose.slides/shapetype).

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```

إرجاع كائن PictureFillFormat لإطار صورة. للقراءة فقط [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**القيمة المرجعة:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```

إرجاع أو تعيين مقياس الارتفاع (نسبيًا إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. للقراءة والكتابة  float .

**القيمة المرجعة:**  
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```

إرجاع أو تعيين مقياس الارتفاع (نسبيًا إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. للقراءة والكتابة  float .

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```

إرجاع أو تعيين مقياس العرض (نسبيًا إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. للقراءة والكتابة  float .

**القيمة المرجعة:**  
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```

إرجاع أو تعيين مقياس العرض (نسبيًا إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تمثل 100٪. للقراءة والكتابة  float .

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### isCameo() {#isCameo--}
```
public final boolean isCameo()
```

تحديد ما إذا كان PictureFrame كائن Cameo أم لا. للقراءة فقط منطقية.

**القيمة المرجعة:**  
boolean