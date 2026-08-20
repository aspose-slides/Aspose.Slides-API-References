---
title: IPictureEffectiveData
second_title: Aspose.Slides for Java API Reference
description: كائن غير قابل للتغيير يحتوي على خصائص الصورة الفعّالة.
type: docs
url: /ar/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

كائن غير قابل للتغيير يحتوي على خصائص الصورة الفعّالة.

--------------------

هذه الواجهة تُستَخدم كجزء من [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) و [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getImage()](#getImage--) | إرجاع الصورة المضمّنة. |
| [getLinkPathLong()](#getLinkPathLong--) | إرجاع عنوان URL للصورة المرتبطة. |
| [getImageTransform()](#getImageTransform--) | إرجاع مجموعة تأثيرات تحويل الصورة. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

إرجاع الصورة المضمّنة. للقراءة فقط [IPPImage](../../com.aspose.slides/ippimage).

**القيمة المرجعة:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

إرجاع عنوان URL للصورة المرتبطة. String للقراءة فقط.

**القيمة المرجعة:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```

إرجاع مجموعة تأثيرات تحويل الصورة. للقراءة فقط [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**القيمة المرجعة:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)