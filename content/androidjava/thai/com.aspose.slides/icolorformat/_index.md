---
title: IColorFormat
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงสีที่ใช้ในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/icolorformat/
---
**ทั้งหมดที่ใช้งานอินเทอร์เฟซ:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

แสดงสีที่ใช้ในงานนำเสนอ.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getColorType()](#getColorType--) | ส่งคืนหรือกำหนดวิธีการกำหนดสี |
| [setColorType(int value)](#setColorType-int-) | ส่งคืนหรือกำหนดวิธีการกำหนดสี |
| [getColor()](#getColor--) | ส่งคืนสีที่ได้ (พร้อมการแปลงสีทั้งหมดที่ถูกนำมาใช้) |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | ส่งคืนสีที่ได้ (พร้อมการแปลงสีทั้งหมดที่ถูกนำมาใช้) |
| [getPresetColor()](#getPresetColor--) | ส่งคืนหรือกำหนดค่าพรีเซ็ตสี |
| [setPresetColor(int value)](#setPresetColor-int-) | ส่งคืนหรือกำหนดค่าพรีเซ็ตสี |
| [getSystemColor()](#getSystemColor--) | ส่งคืนหรือกำหนดสีที่ระบุโดยตารางสีของระบบ |
| [setSystemColor(int value)](#setSystemColor-int-) | ส่งคืนหรือกำหนดสีที่ระบุโดยตารางสีของระบบ |
| [getSchemeColor()](#getSchemeColor--) | ส่งคืนหรือกำหนดสีที่ระบุโดยโครงสร้างสี |
| [setSchemeColor(int value)](#setSchemeColor-int-) | ส่งคืนหรือกำหนดสีที่ระบุโดยโครงสร้างสี |
| [getR()](#getR--) | ส่งคืนหรือกำหนดคอมโพเนนต์สีแดงของสี |
| [setR(byte value)](#setR-byte-) | ส่งคืนหรือกำหนดคอมโพเนนต์สีแดงของสี |
| [getG()](#getG--) | ส่งคืนหรือกำหนดคอมโพเนนต์สีเขียวของสี |
| [setG(byte value)](#setG-byte-) | ส่งคืนหรือกำหนดคอมโพเนนต์สีเขียวของสี |
| [getB()](#getB--) | ส่งคืนหรือกำหนดคอมโพเนนต์สีน้ำเงินของสี |
| [setB(byte value)](#setB-byte-) | ส่งคืนหรือกำหนดคอมโพเนนต์สีน้ำเงินของสี |
| [getFloatR()](#getFloatR--) | ส่งคืนหรือกำหนดคอมโพเนนต์สีแดงของสี |
| [setFloatR(float value)](#setFloatR-float-) | ส่งคืนหรือกำหนดคอมโพเนนต์สีแดงของสี |
| [getFloatG()](#getFloatG--) | ส่งคืนหรือกำหนดคอมโพเนนต์สีเขียวของสี |
| [setFloatG(float value)](#setFloatG-float-) | ส่งคืนหรือกำหนดคอมโพเนนต์สีเขียวของสี |
| [getFloatB()](#getFloatB--) | ส่งคืนหรือกำหนดคอมโพเนนต์สีน้ำเงินของสี |
| [setFloatB(float value)](#setFloatB-float-) | ส่งคืนหรือกำหนดคอมโพเนนต์สีน้ำเงินของสี |
| [getHue()](#getHue--) | ส่งคืนหรือกำหนดคอมโพเนนต์สี hue ของสีในรูปแบบ HSL |
| [setHue(float value)](#setHue-float-) | ส่งคืนหรือกำหนดคอมโพเนนต์สี hue ของสีในรูปแบบ HSL |
| [getSaturation()](#getSaturation--) | ส่งคืนหรือกำหนดคอมโพเนนต์ความอิ่มตัวของสีในรูปแบบ HSL |
| [setSaturation(float value)](#setSaturation-float-) | ส่งคืนหรือกำหนดคอมโพเนนต์ความอิ่มตัวของสีในรูปแบบ HSL |
| [getLuminance()](#getLuminance--) | ส่งคืนหรือกำหนดคอมโพเนนต์ความสว่างของสีในรูปแบบ HSL |
| [setLuminance(float value)](#setLuminance-float-) | ส่งคืนหรือกำหนดคอมโพเนนต์ความสว่างของสีในรูปแบบ HSL |
| [getColorTransform()](#getColorTransform--) | ส่งคืนคอลเลกชันของการแปลงสีที่ถูกใช้กับสี |
| [toString(int format)](#toString-int-) | ส่งคืนสตริงที่แสดงรูปแบบสีปัจจุบัน |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | คัดลอกรูปแบบสีจาก "color". |

### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

ส่งคืนหรือกำหนดวิธีการกำหนดสี. อ่าน/เขียน [ColorType](../../com.aspose.slides/colortype).

**ส่งคืน:**
int

### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

ส่งคืนหรือกำหนดวิธีการกำหนดสี. อ่าน/เขียน [ColorType](../../com.aspose.slides/colortype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```

ส่งคืนสีที่ได้ (พร้อมการแปลงสีทั้งหมดที่ถูกนำมาใช้). ตั้งค่าสี RGB และล้างการแปลงสีทั้งหมด. อ่าน/เขียน java.lang.Integer.

**ส่งคืน:**
java.lang.Integer

### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

ส่งคืนสีที่ได้ (พร้อมการแปลงสีทั้งหมดที่ถูกนำมาใช้). ตั้งค่าสี RGB และล้างการแปลงสีทั้งหมด. อ่าน/เขียน java.lang.Integer.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

ส่งคืนหรือกำหนดค่าพรีเซ็ตสี. อ่าน/เขียน [PresetColor](../../com.aspose.slides/presetcolor).

**ส่งคืน:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

ส่งคืนหรือกำหนดค่าพรีเซ็ตสี. อ่าน/เขียน [PresetColor](../../com.aspose.slides/presetcolor).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

ส่งคืนหรือกำหนดสีที่ระบุโดยตารางสีของระบบ. อ่าน/เขียน [SystemColor](../../com.aspose.slides/systemcolor).

**ส่งคืน:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

ส่งคืนหรือกำหนดสีที่ระบุโดยตารางสีของระบบ. อ่าน/เขียน [SystemColor](../../com.aspose.slides/systemcolor).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

ส่งคืนหรือกำหนดสีที่ระบุโดยโครงสร้างสี. อ่าน/เขียน [SchemeColor](../../com.aspose.slides/schemecolor).

**ส่งคืน:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

ส่งคืนหรือกำหนดสีที่ระบุโดยโครงสร้างสี. อ่าน/เขียน [SchemeColor](../../com.aspose.slides/schemecolor).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```

ส่งคืนหรือกำหนดคอมโพเนนต์สีแดงของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน byte.

**ส่งคืน:**
byte

### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

ส่งคืนหรือกำหนดคอมโพเนนต์สีแดงของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```

ส่งคืนหรือกำหนดคอมโพเนนต์สีเขียวของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน byte.

**ส่งคืน:**
byte

### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

ส่งคืนหรือกำหนดคอมโพเนนต์สีเขียวของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```

ส่งคืนหรือกำหนดคอมโพเนนต์สีน้ำเงินของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน byte.

**ส่งคืน:**
byte

### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

ส่งคืนหรือกำหนดคอมโพเนนต์สีน้ำเงินของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

ส่งคืนหรือกำหนดคอมโพเนนต์สีแดงของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**ส่งคืน:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

ส่งคืนหรือกำหนดคอมโพเนนต์สีแดงของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

ส่งคืนหรือกำหนดคอมโพเนนต์สีเขียวของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**ส่งคืน:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

ส่งคืนหรือกำหนดคอมโพเนนต์สีเขียวของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

ส่งคืนหรือกำหนดคอมโพเนนต์สีน้ำเงินของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**ส่งคืน:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

ส่งคืนหรือกำหนดคอมโพเนนต์สีน้ำเงินของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```

ส่งคืนหรือกำหนดคอมโพเนนต์สี hue ของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**ส่งคืน:**
float

### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

ส่งคืนหรือกำหนดคอมโพเนนต์สี hue ของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

ส่งคืนหรือกำหนดคอมโพเนนต์ความอิ่มตัวของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**ส่งคืน:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

ส่งคืนหรือกำหนดคอมโพเนนต์ความอิ่มตัวของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

ส่งคืนหรือกำหนดคอมโพเนนต์ความสว่างของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**ส่งคืน:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

ส่งคืนหรือกำหนดคอมโพเนนต์ความสว่างของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

ส่งคืนคอลเลกชันของการแปลงสีที่ถูกใช้กับสี. อ่านอย่างเดียว [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**ส่งคืน:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

ส่งคืนสตริงที่แสดงรูปแบบสีปัจจุบัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| format | int | ประเภทของรูปแบบสตริงสี |

**ส่งคืน:**
java.lang.String - สตริงที่แสดงรูปแบบสีปัจจุบัน

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

คัดลอกรูปแบบสีจาก "color".

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Color [IColorFormat](../../com.aspose.slides/icolorformat) |