---
title: IFillOverlay
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงเอฟเฟกต์ Fill Overlay
type: docs
url: /th/com.aspose.slides/ifilloverlay/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

แสดงถึงเอฟเฟกต์ Fill Overlay. Fill overlay สามารถใช้เพื่อระบุการเติมสีเพิ่มเติมสำหรับอ็อบเจกต์และผสานการเติมสีสองชั้นเข้าด้วยกัน.
## เมธอด

| เมธอด | คำอธิบาย |
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Fill format. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)