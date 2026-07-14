---
title: IColorChange
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงเอฟเฟกต์การเปลี่ยนสี.
type: docs
url: /th/com.aspose.slides/icolorchange/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

แสดงเอฟเฟกต์การเปลี่ยนสี. อินสแตนซ์ของ FromColor จะถูกแทนที่ด้วยอินสแตนซ์ของ ToColor.
## เมธอด

| เมธodb | คำอธิบาย |
| --- | --- |
| [getFromColor()](#getFromColor--) | สีที่จะแทนที่. |
| [getToColor()](#getToColor--) | สีที่จะใช้แทนที่. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```

สีที่จะแทนที่. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```

สีที่จะใช้แทนที่. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)