---
title: IColorChangeEffectiveData
second_title: Aspose.Slides สำหรับ API ของ Java
description: อ็อบเจกต์ที่ไม่เปลี่ยนแปลงซึ่งแสดงถึงเอฟเฟกต์การเปลี่ยนสี.
type: docs
url: /th/com.aspose.slides/icolorchangeeffectivedata/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

อ็อบเจกต์ที่ไม่เปลี่ยนแปลงซึ่งแสดงถึงเอฟเฟกต์การเปลี่ยนสี ตัวอย่างของ FromColor จะถูกแทนที่ด้วยตัวอย่างของ ToColor.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFromColor()](#getFromColor--) | สีที่จะถูกแทนที่. |
| [getToColor()](#getToColor--) | สีที่จะใช้แทนที่. |
| [getUseAlpha()](#getUseAlpha--) | คืนค่า boolean ที่กำหนดว่าควรใช้ส่วนประกอบ alpha หรือไม่. |
### getFromColor() {#getFromColor--}
```
public abstract Color getFromColor()
```


สีที่จะถูกแทนที่. อ่านอย่างเดียว java.awt.Color.

**คืนค่า:**
java.awt.Color
### getToColor() {#getToColor--}
```
public abstract Color getToColor()
```


สีที่จะใช้แทนที่. อ่านอย่างเดียว java.awt.Color.

**คืนค่า:**
java.awt.Color
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```


คืนค่า boolean ที่กำหนดว่าควรใช้ส่วนประกอบ alpha หรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean