---
title: IColorChange
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงเอฟเฟกต์การเปลี่ยนสี.
type: docs
url: /th/com.aspose.slides/icolorchange/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

แสดงถึงเอฟเฟกต์การเปลี่ยนสี ตัวอย่างของ FromColor จะถูกแทนที่ด้วยตัวอย่างของ ToColor.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFromColor()](#getFromColor--) | สีที่จะแทนที่. |
| [getToColor()](#getToColor--) | สีที่จะใช้แทน. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```

สีที่จะแทนที่. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**ผลลัพธ์:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```

สีที่จะใช้แทน. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**ผลลัพธ์:**
[IColorFormat](../../com.aspose.slides/icolorformat)