---
title: IFillOverlay
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: เป็นการแทนเอฟเฟกต์ Fill Overlay.
type: docs
url: /th/com.aspose.slides/ifilloverlay/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

เป็นการแทนเอฟเฟกต์ Fill Overlay. Fill overlay สามารถใช้เพื่อระบุการเติมเพิ่มเติมสำหรับวัตถุและผสานการเติมสองอย่างเข้าด้วยกัน
## วิธีการ

| Method | Description |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```

FillBlendMode. อ่าน/เขียน [FillBlendMode](../../com.aspose.slides/fillblendmode).

**คืนค่า:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```

FillBlendMode. อ่าน/เขียน [FillBlendMode](../../com.aspose.slides/fillblendmode).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Fill format. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)