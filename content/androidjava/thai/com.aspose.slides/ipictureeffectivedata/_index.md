---
title: IPictureEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective picture properties.
type: docs
url: /th/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

อ็อบเจกต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติโปรไฟล์ภาพที่มีประสิทธิภาพ

--------------------

อินเทอร์เฟซนี้ใช้เป็นส่วนหนึ่งของ [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) และ [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getImage()](#getImage--) | ส่งคืนภาพที่ฝังไว้ |
| [getLinkPathLong()](#getLinkPathLong--) | ส่งคืน URL ของภาพที่เชื่อมโยง |
| [getImageTransform()](#getImageTransform--) | ส่งคืนคอลเลกชันของเอฟเฟกต์การแปลงภาพ |

### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

ส่งคืนภาพที่ฝังไว้ อ่านอย่างเดียว [IPPImage](../../com.aspose.slides/ippimage).

**ส่งคืน:**  
[IPPImage](../../com.aspose.slides/ippimage)

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

ส่งคืน URL ของภาพที่เชื่อมโยง อ่านอย่างเดียว String.

**ส่งคืน:**  
java.lang.String

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```

ส่งคืนคอลเลกชันของเอฟเฟกต์การแปลงภาพ อ่านอย่างเดียว [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**ส่งคืน:**  
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)