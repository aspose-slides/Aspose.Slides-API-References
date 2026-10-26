---
title: IPictureEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective picture properties.
type: docs
url: /ar/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

كائن غير قابل للتغيير يحتوي على خصائص الصورة الفعالة.

--------------------

يتم استخدام هذه الواجهة كجزء من [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) و [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getImage()](#getImage--) | Returns the embedded image. |
| [getLinkPathLong()](#getLinkPathLong--) | Returns linked image's URL. |
| [getImageTransform()](#getImageTransform--) | Returns the collection of image transform effects. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


يرجع الصورة المدمجة. للقراءة فقط [IPPImage](../../com.aspose.slides/ippimage).

**القيمة المرجعة:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


يرجع عنوان URL للصورة المرتبطة. للقراءة فقط String.

**القيمة المرجعة:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```


يرجع مجموعة تأثيرات تحويل الصورة. للقراءة فقط [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**القيمة المرجعة:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)