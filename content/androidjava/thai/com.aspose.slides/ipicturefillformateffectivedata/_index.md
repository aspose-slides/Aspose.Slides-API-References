---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ออบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติของการเติมรูปภาพ.
type: docs
url: /th/com.aspose.slides/ipicturefillformateffectivedata/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

ออบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติของการเติมรูปภาพ

--------------------

อินเทอร์เฟซนี้ใช้เป็นส่วนหนึ่งของ [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getDpi()](#getDpi--) | คืนค่า dpi ที่ใช้เพื่อเติมรูปภาพ |
| [getPictureFillMode()](#getPictureFillMode--) | คืนค่าโหมดการเติมรูปภาพ |
| [getPicture()](#getPicture--) | คืนค่ารูปภาพ |
| [getCropLeft()](#getCropLeft--) | คืนค่าจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ถูกตัดออกจากด้านซ้ายของรูปภาพ |
| [getCropTop()](#getCropTop--) | คืนค่าจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ถูกตัดออกจากด้านบนของรูปภาพ |
| [getCropRight()](#getCropRight--) | คืนค่าจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ถูกตัดออกจากด้านขวาของรูปภาพ |
| [getCropBottom()](#getCropBottom--) | คืนค่าจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ถูกตัดออกจากด้านล่างของรูปภาพ |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

คืนค่า dpi ที่ใช้เพื่อเติมรูปภาพ. อ่าน-อย่างเดียว int.

**คืนค่า:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

คืนค่าโหมดการเติมรูปภาพ. อ่าน-อย่างเดียว [PictureFillMode](../../com.aspose.slides/picturefillmode).

**คืนค่า:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

คืนค่ารูปภาพ. อ่าน-อย่างเดียว [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**คืนค่า:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

คืนค่าจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ถูกตัดออกจากด้านซ้ายของรูปภาพ. อ่าน-อย่างเดียว float.

**คืนค่า:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

คืนค่าจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ถูกตัดออกจากด้านบนของรูปภาพ. อ่าน-อย่างเดียว float.

**คืนค่า:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

คืนค่าจำนวนเปอร์เซ็นต์ของความกว้างภาพจริงที่ถูกตัดออกจากด้านขวาของรูปภาพ. อ่าน-อย่างเดียว float.

**คืนค่า:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

คืนค่าจำนวนเปอร์เซ็นต์ของความสูงภาพจริงที่ถูกตัดออกจากด้านล่างของรูปภาพ. อ่าน-อย่างเดียว float.

**คืนค่า:**
float