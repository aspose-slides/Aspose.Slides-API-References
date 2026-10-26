---
title: IPictureEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective picture properties.
type: docs
url: /th/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

อ็อบเจ็กต์ที่ไม่สามารถเปลี่ยนแปลงได้ซึ่งบรรจุคุณสมบัติของรูปภาพที่มีผล

--------------------

อินเทอร์เฟซนี้ใช้เป็นส่วนหนึ่งของ [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) and [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getImage()](#getImage--) | คืนค่าภาพที่ฝังอยู่ |
| [getLinkPathLong()](#getLinkPathLong--) | คืนค่า URL ของภาพที่ลิงก์ |
| [getImageTransform()](#getImageTransform--) | คืนค่าคอลเลกชันของเอฟเฟกต์การแปลงภาพ |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

คืนค่าภาพที่ฝังอยู่. อ่านอย่างเดียว [IPPImage](../../com.aspose.slides/ippimage).

**คืนค่า:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

คืนค่า URL ของภาพที่ลิงก์. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```

คืนค่าคอลเลกชันของเอฟเฟกต์การแปลงภาพ. อ่านอย่างเดียว [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**คืนค่า:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)