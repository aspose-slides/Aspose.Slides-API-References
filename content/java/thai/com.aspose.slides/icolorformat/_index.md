---
title: IColorFormat
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: เป็นตัวแทนของสีที่ใช้ในการนำเสนอ.
type: docs
url: /th/com.aspose.slides/icolorformat/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

เป็นตัวแทนของสีที่ใช้ในการนำเสนอ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getColorType()](#getColorType--) | คืนค่า หรือกำหนดวิธีการกำหนดสี. |
| [setColorType(int value)](#setColorType-int-) | คืนค่า หรือกำหนดวิธีการกำหนดสี. |
| [getColor()](#getColor--) | คืนค่าสีที่ได้ (โดยมีการแปลงสีทั้งหมดที่ใช้). |
| [setColor(Color value)](#setColor-java.awt.Color-) | คืนค่าสีที่ได้ (โดยมีการแปลงสีทั้งหมดที่ใช้). |
| [getPresetColor()](#getPresetColor--) | คืนค่า หรือกำหนดค่าสีสำเร็จรูป. |
| [setPresetColor(int value)](#setPresetColor-int-) | คืนค่า หรือกำหนดค่าสีสำเร็จรูป. |
| [getSystemColor()](#getSystemColor--) | คืนค่า หรือกำหนดสีที่ระบุโดยตารางสีระบบ. |
| [setSystemColor(int value)](#setSystemColor-int-) | คืนค่า หรือกำหนดสีที่ระบุโดยตารางสีระบบ. |
| [getSchemeColor()](#getSchemeColor--) | คืนค่า หรือกำหนดสีที่ระบุโดยชุดสี. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | คืนค่า หรือกำหนดสีที่ระบุโดยชุดสี. |
| [getR()](#getR--) | คืนค่า หรือกำหนดส่วนสีแดงของสี. |
| [setR(byte value)](#setR-byte-) | คืนค่า หรือกำหนดส่วนสีแดงของสี. |
| [getG()](#getG--) | คืนค่า หรือกำหนดส่วนสีเขียวของสี. |
| [setG(byte value)](#setG-byte-) | คืนค่า หรือกำหนดส่วนสีเขียวของสี. |
| [getB()](#getB--) | คืนค่า หรือกำหนดส่วนสีน้ำเงินของสี. |
| [setB(byte value)](#setB-byte-) | คืนค่า หรือกำหนดส่วนสีน้ำเงินของสี. |
| [getFloatR()](#getFloatR--) | คืนค่า หรือกำหนดส่วนสีแดงของสี. |
| [setFloatR(float value)](#setFloatR-float-) | คืนค่า หรือกำหนดส่วนสีแดงของสี. |
| [getFloatG()](#getFloatG--) | คืนค่า หรือกำหนดส่วนสีเขียวของสี. |
| [setFloatG(float value)](#setFloatG-float-) | คืนค่า หรือกำหนดส่วนสีเขียวของสี. |
| [getFloatB()](#getFloatB--) | คืนค่า หรือกำหนดส่วนสีน้ำเงินของสี. |
| [setFloatB(float value)](#setFloatB-float-) | คืนค่า หรือกำหนดส่วนสีน้ำเงินของสี. |
| [getHue()](#getHue--) | คืนค่า หรือกำหนดส่วน hue ของสีในรูปแบบ HSL. |
| [setHue(float value)](#setHue-float-) | คืนค่า หรือกำหนดส่วน hue ของสีในรูปแบบ HSL. |
| [getSaturation()](#getSaturation--) | คืนค่า หรือกำหนดส่วนความอิ่มของสีในรูปแบบ HSL. |
| [setSaturation(float value)](#setSaturation-float-) | คืนค่า หรือกำหนดส่วนความอิ่มของสีในรูปแบบ HSL. |
| [getLuminance()](#getLuminance--) | คืนค่า หรือกำหนดส่วนความสว่างของสีในรูปแบบ HSL. |
| [setLuminance(float value)](#setLuminance-float-) | คืนค่า หรือกำหนดส่วนความสว่างของสีในรูปแบบ HSL. |
| [getColorTransform()](#getColorTransform--) | คืนคอลเลกชันของการแปลงสีที่ใช้กับสี. |
| [toString(int format)](#toString-int-) | คืนค่า String ที่แสดงรูปแบบสีปัจจุบัน. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | คัดลอกรูปแบบสีจาก "color". |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

คืนค่า หรือกำหนดวิธีการกำหนดสี. อ่าน/เขียน [ColorType](../../com.aspose.slides/colortype).

**คืนค่า:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

คืนค่า หรือกำหนดวิธีการกำหนดสี. อ่าน/เขียน [ColorType](../../com.aspose.slides/colortype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public abstract Color getColor()
```

คืนค่าสีที่ได้ (โดยมีการแปลงสีทั้งหมดที่ใช้). ตั้งค่า RGB และล้างการแปลงสีทั้งหมด. อ่าน/เขียน java.awt.Color.

**คืนค่า:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

คืนค่าสีที่ได้ (โดยมีการแปลงสีทั้งหมดที่ใช้). ตั้งค่า RGB และล้างการแปลงสีทั้งหมด. อ่าน/เขียน java.awt.Color.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.awt.Color |  |
### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

คืนค่า หรือกำหนดค่าสีสำเร็จรูป. อ่าน/เขียน [PresetColor](../../com.aspose.slides/presetcolor).

**คืนค่า:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

คืนค่า หรือกำหนดค่าสีสำเร็จรูป. อ่าน/เขียน [PresetColor](../../com.aspose.slides/presetcolor).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

คืนค่า หรือกำหนดสีที่ระบุโดยตารางสีระบบ. อ่าน/เขียน [SystemColor](../../com.aspose.slides/systemcolor).

**คืนค่า:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

คืนค่า หรือกำหนดสีที่ระบุโดยตารางสีระบบ. อ่าน/เขียน [SystemColor](../../com.aspose.slides/systemcolor).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

คืนค่า หรือกำหนดสีที่ระบุโดยชุดสี. อ่าน/เขียน [SchemeColor](../../com.aspose.slides/schemecolor).

**คืนค่า:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

คืนค่า หรือกำหนดสีที่ระบุโดยชุดสี. อ่าน/เขียน [SchemeColor](../../com.aspose.slides/schemecolor).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public abstract byte getR()
```

คืนค่า หรือกำหนดส่วนสีแดงของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน byte.

**คืนค่า:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

คืนค่า หรือกำหนดส่วนสีแดงของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public abstract byte getG()
```

คืนค่า หรือกำหนดส่วนสีเขียวของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน byte.

**คืนค่า:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

คืนค่า หรือกำหนดส่วนสีเขียวของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public abstract byte getB()
```

คืนค่า หรือกำหนดส่วนสีน้ำเงินของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน byte.

**คืนค่า:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

คืนค่า หรือกำหนดส่วนสีน้ำเงินของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

คืนค่า หรือกำหนดส่วนสีแดงของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**คืนค่า:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

คืนค่า หรือกำหนดส่วนสีแดงของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

คืนค่า หรือกำหนดส่วนสีเขียวของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**คืนค่า:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

คืนค่า หรือกำหนดส่วนสีเขียวของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

คืนค่า หรือกำหนดส่วนสีน้ำเงินของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**คืนค่า:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

คืนค่า หรือกำหนดส่วนสีน้ำเงินของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public abstract float getHue()
```

คืนค่า หรือกำหนดส่วน hue ของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**คืนค่า:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

คืนค่า หรือกำหนดส่วน hue ของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

คืนค่า หรือกำหนดส่วนความอิ่มของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**คืนค่า:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

คืนค่า หรือกำหนดส่วนความอิ่มของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

คืนค่า หรือกำหนดส่วนความสว่างของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**คืนค่า:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

คืนค่า หรือกำหนดส่วนความสว่างของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

คืนคอลเลกชันของการแปลงสีที่ใช้กับสี. อ่านอย่างเดียว [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**คืนค่า:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

คืนค่า String ที่แสดงรูปแบบสีปัจจุบัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| format | int | ชนิดของรูปแบบสตริงสี. |

**คืนค่า:**
java.lang.String - A string that represents the current color format.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

คัดลอกรูปแบบสีจาก "color".

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Color [IColorFormat](../../com.aspose.slides/icolorformat) |