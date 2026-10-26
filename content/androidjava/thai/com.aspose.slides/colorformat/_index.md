---
title: ColorFormat
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงสีที่ใช้ในงานนำเสนอ
type: docs
url: /th/com.aspose.slides/colorformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IColorFormat](../../com.aspose.slides/icolorformat)
```
public final class ColorFormat extends PVIObject implements IColorFormat
```

Represents a color used in a presentation.
## เมธอด

| Method | Description |
| --- | --- |
| [getColorType()](#getColorType--) | คืนค่า หรือ ตั้งค่าวิธีการกำหนดสี. |
| [setColorType(int value)](#setColorType-int-) | คืนค่า หรือ ตั้งค่าวิธีการกำหนดสี. |
| [getColor()](#getColor--) | คืนค่าสีที่ได้ (โดยมีการแปลงสีทั้งหมดที่ถูกนำไปใช้). |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | คืนค่าสีที่ได้ (โดยมีการแปลงสีทั้งหมดที่ถูกนำไปใช้). |
| [getPresetColor()](#getPresetColor--) | คืนค่า หรือ ตั้งค่าสีพรีเซ็ต. |
| [setPresetColor(int value)](#setPresetColor-int-) | คืนค่า หรือ ตั้งค่าสีพรีเซ็ต. |
| [getSystemColor()](#getSystemColor--) | คืนค่า หรือ ตั้งค่าสีที่ระบุโดยตารางสีระบบ. |
| [setSystemColor(int value)](#setSystemColor-int-) | คืนค่า หรือ ตั้งค่าสีที่ระบุโดยตารางสีระบบ. |
| [getSchemeColor()](#getSchemeColor--) | คืนค่า หรือ ตั้งค่าสีที่ระบุโดยโครงสร้างสี. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | คืนค่า หรือ ตั้งค่าสีที่ระบุโดยโครงสร้างสี. |
| [getR()](#getR--) | คืนค่า หรือ ตั้งค่าส่วนสีแดงของสี. |
| [setR(byte value)](#setR-byte-) | คืนค่า หรือ ตั้งค่าส่วนสีแดงของสี. |
| [getG()](#getG--) | คืนค่า หรือ ตั้งค่าส่วนสีเขียวของสี. |
| [setG(byte value)](#setG-byte-) | คืนค่า หรือ ตั้งค่าส่วนสีเขียวของสี. |
| [getB()](#getB--) | คืนค่า หรือ ตั้งค่าส่วนสีน้ำเงินของสี. |
| [setB(byte value)](#setB-byte-) | คืนค่า หรือ ตั้งค่าส่วนสีน้ำเงินของสี. |
| [getFloatR()](#getFloatR--) | คืนค่า หรือ ตั้งค่าส่วนสีแดงของสี. |
| [setFloatR(float value)](#setFloatR-float-) | คืนค่า หรือ ตั้งค่าส่วนสีแดงของสี. |
| [getFloatG()](#getFloatG--) | คืนค่า หรือ ตั้งค่าส่วนสีเขียวของสี. |
| [setFloatG(float value)](#setFloatG-float-) | คืนค่า หรือ ตั้งค่าส่วนสีเขียวของสี. |
| [getFloatB()](#getFloatB--) | คืนค่า หรือ ตั้งค่าส่วนสีน้ำเงินของสี. |
| [setFloatB(float value)](#setFloatB-float-) | คืนค่า หรือ ตั้งค่าส่วนสีน้ำเงินของสี. |
| [getHue()](#getHue--) | คืนค่า หรือ ตั้งค่าส่วนสี Hue ของสีในรูปแบบ HSL. |
| [setHue(float value)](#setHue-float-) | คืนค่า หรือ ตั้งค่าส่วนสี Hue ของสีในรูปแบบ HSL. |
| [getSaturation()](#getSaturation--) | คืนค่า หรือ ตั้งค่าส่วนความอิ่มตัวของสีในรูปแบบ HSL. |
| [setSaturation(float value)](#setSaturation-float-) | คืนค่า หรือ ตั้งค่าส่วนความอิ่มตัวของสีในรูปแบบ HSL. |
| [getLuminance()](#getLuminance--) | คืนค่า หรือ ตั้งค่าส่วนความสว่างของสีในรูปแบบ HSL. |
| [setLuminance(float value)](#setLuminance-float-) | คืนค่า หรือ ตั้งค่าส่วนความสว่างของสีในรูปแบบ HSL. |
| [getColorTransform()](#getColorTransform--) | คืนค่าชุดของการแปลงสีที่ใช้กับสี. |
| [toString(int format)](#toString-int-) | คืนค่า String ที่แสดงรูปแบบสีปัจจุบัน. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | คัดลอกรูปแบบสีจาก "color". |
| [equals(Object obj)](#equals-java.lang.Object-) | ตรวจสอบความเท่ากันกับอ็อบเจ็กต์ที่ระบุ. |
| [hashCode()](#hashCode--) | คืนค่า hash code. |
| [getVersion()](#getVersion--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getColorType() {#getColorType--}
```
public final int getColorType()
```

คืนค่า หรือ ตั้งค่าวิธีการกำหนดสี. อ่าน/เขียน [ColorType](../../com.aspose.slides/colortype).

**คืนค่า:**
int

### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```

คืนค่า หรือ ตั้งค่าวิธีการกำหนดสี. อ่าน/เขียน [ColorType](../../com.aspose.slides/colortype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public final Integer getColor()
```

คืนค่าสีที่ได้ (โดยมีการแปลงสีทั้งหมดที่ถูกนำไปใช้). ตั้งค่า RGB และล้างการแปลงสีทั้งหมด. อ่าน/เขียน java.lang.Integer.

**คืนค่า:**
java.lang.Integer

### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```

คืนค่าสีที่ได้ (โดยมีการแปลงสีทั้งหมดที่ถูกนำไปใช้). ตั้งค่า RGB และล้างการแปลงสีทั้งหมด. อ่าน/เขียน java.lang.Integer.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPresetColor() {#getPresetColor--}
```
public final int getPresetColor()
```

คืนค่า หรือ ตั้งค่าสีพรีเซ็ต. อ่าน/เขียน [PresetColor](../../com.aspose.slides/presetcolor).

**คืนค่า:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public final void setPresetColor(int value)
```

คืนค่า หรือ ตั้งค่าสีพรีเซ็ต. อ่าน/เขียน [PresetColor](../../com.aspose.slides/presetcolor).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public final int getSystemColor()
```

คืนค่า หรือ ตั้งค่าสีที่ระบุโดยตารางสีระบบ. อ่าน/เขียน [SystemColor](../../com.aspose.slides/systemcolor).

**คืนค่า:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public final void setSystemColor(int value)
```

คืนค่า หรือ ตั้งค่าสีที่ระบุโดยตารางสีระบบ. อ่าน/เขียน [SystemColor](../../com.aspose.slides/systemcolor).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public final int getSchemeColor()
```

คืนค่า หรือ ตั้งค่าสีที่ระบุโดยโครงสร้างสี. อ่าน/เขียน [SchemeColor](../../com.aspose.slides/schemecolor).

**คืนค่า:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public final void setSchemeColor(int value)
```

คืนค่า หรือ ตั้งค่าสีที่ระบุโดยโครงสร้างสี. อ่าน/เขียน [SchemeColor](../../com.aspose.slides/schemecolor).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public final byte getR()
```

คืนค่า หรือ ตั้งค่าส่วนสีแดงของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  byte .

**คืนค่า:**
byte

### setR(byte value) {#setR-byte-}
```
public final void setR(byte value)
```

คืนค่า หรือ ตั้งค่าส่วนสีแดงของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  byte .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public final byte getG()
```

คืนค่า หรือ ตั้งค่าส่วนสีเขียวของสี. การแปลงสีทั้งหมดจะถูกละเว้น.

**คืนค่า:**
byte

### setG(byte value) {#setG-byte-}
```
public final void setG(byte value)
```

คืนค่า หรือ ตั้งค่าส่วนสีเขียวของสี. การแปลงสีทั้งหมดจะถูกละเว้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public final byte getB()
```

คืนค่า หรือ ตั้งค่าส่วนสีน้ำเงินของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  byte .

**คืนค่า:**
byte

### setB(byte value) {#setB-byte-}
```
public final void setB(byte value)
```

คืนค่า หรือ ตั้งค่าส่วนสีน้ำเงินของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  byte .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public final float getFloatR()
```

คืนค่า หรือ ตั้งค่าส่วนสีแดงของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**คืนค่า:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public final void setFloatR(float value)
```

คืนค่า หรือ ตั้งค่าส่วนสีแดงของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public final float getFloatG()
```

คืนค่า หรือ ตั้งค่าส่วนสีเขียวของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**คืนค่า:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public final void setFloatG(float value)
```

คืนค่า หรือ ตั้งค่าส่วนสีเขียวของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public final float getFloatB()
```

คืนค่า หรือ ตั้งค่าส่วนสีน้ำเงินของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**คืนค่า:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public final void setFloatB(float value)
```

คืนค่า หรือ ตั้งค่าส่วนสีน้ำเงินของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public final float getHue()
```

คืนค่า หรือ ตั้งค่าส่วนสี Hue ของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**คืนค่า:**
float

### setHue(float value) {#setHue-float-}
```
public final void setHue(float value)
```

คืนค่า หรือ ตั้งค่าส่วนสี Hue ของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```

คืนค่า หรือ ตั้งค่าส่วนความอิ่มตัวของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**คืนค่า:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public final void setSaturation(float value)
```

คืนค่า หรือ ตั้งค่าส่วนความอิ่มตัวของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public final float getLuminance()
```

คืนค่า หรือ ตั้งค่าส่วนความสว่างของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**คืนค่า:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public final void setLuminance(float value)
```

คืนค่า หรือ ตั้งค่าส่วนความสว่างของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public final IColorOperationCollection getColorTransform()
```

คืนค่าชุดของการแปลงสีที่ใช้กับสี. อ่านอย่างเดียว [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**คืนค่า:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public final String toString(int format)
```

คืนค่า String ที่แสดงรูปแบบสีปัจจุบัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| format | int | ประเภทของรูปแบบสตริงสี. |

**คืนค่า:**
java.lang.String - สตริงที่แสดงรูปแบบสีปัจจุบัน.

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public final void copyFrom(IColorFormat color)
```

คัดลอกรูปแบบสีจาก "color".

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

ตรวจสอบความเท่ากันกับอ็อบเจ็กต์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | อ็อบเจ็กต์. |

**คืนค่า:**
boolean - true หากอ็อบเจ็กต์เท่ากัน, มิฉะนั้น false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

คืนค่า hash code.

**คืนค่า:**
int - Hash code.

### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public final ISlideComponent getParent_ISlideComponent()
```

**คืนค่า:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

คืนค่า parent IPresentationComponent. อ่านอย่างเดียว [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**คืนค่า:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)