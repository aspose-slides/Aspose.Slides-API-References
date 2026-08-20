---
title: ColorFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แทนสีที่ใช้ในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/colorformat/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IColorFormat](../../com.aspose.slides/icolorformat)
```
public final class ColorFormat extends PVIObject implements IColorFormat
```

แทนสีที่ใช้ในงานนำเสนอ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getColorType()](#getColorType--) | คืนค่า หรือกำหนดวิธีการกำหนดสี. |
| [setColorType(int value)](#setColorType-int-) | คืนค่า หรือกำหนดวิธีการกำหนดสี. |
| [getColor()](#getColor--) | คืนค่าสีที่ได้ (โดยใช้การแปลงสีทั้งหมด). |
| [setColor(Color value)](#setColor-java.awt.Color-) | คืนค่าสีที่ได้ (โดยใช้การแปลงสีทั้งหมด). |
| [getPresetColor()](#getPresetColor--) | คืนค่า หรือกำหนดค่าสีตั้งล่วงหน้า. |
| [setPresetColor(int value)](#setPresetColor-int-) | คืนค่า หรือกำหนดค่าสีตั้งล่วงหน้า. |
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
| [getColorTransform()](#getColorTransform--) | คืนคอลเลกชันของการแปลงสีที่ถูกนำไปใช้กับสี. |
| [toString(int format)](#toString-int-) | คืนค่า String ที่แสดงรูปแบบสีปัจจุบัน. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | คัดลอกรูปแบบสีจาก "color". |
| [equals(Object obj)](#equals-java.lang.Object-) | ตรวจสอบความเท่ากันกับอ็อบเจกต์ที่ระบุ. |
| [hashCode()](#hashCode--) | คืนค่า hash code. |
| [getVersion()](#getVersion--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getColorType() {#getColorType--}
```
public final int getColorType()
```

คืนค่า หรือกำหนดวิธีการกำหนดสี. อ่าน/เขียน [ColorType](../../com.aspose.slides/colortype).

**คืนค่า:**
int

### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```

คืนค่า หรือกำหนดวิธีการกำหนดสี. อ่าน/เขียน [ColorType](../../com.aspose.slides/colortype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public final Color getColor()
```

คืนค่าสีที่ได้ (โดยใช้การแปลงสีทั้งหมด). ตั้งค่าสี RGB และเคลียร์การแปลงสีทั้งหมด. อ่าน/เขียน java.awt.Color.

**คืนค่า:**
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

คืนค่าสีที่ได้ (โดยใช้การแปลงสีทั้งหมด). ตั้งค่าสี RGB และเคลียร์การแปลงสีทั้งหมด. อ่าน/เขียน java.awt.Color.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public final int getPresetColor()
```

คืนค่า หรือกำหนดค่าสีตั้งล่วงหน้า. อ่าน/เขียน [PresetColor](../../com.aspose.slides/presetcolor).

**คืนค่า:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public final void setPresetColor(int value)
```

คืนค่า หรือกำหนดค่าสีตั้งล่วงหน้า. อ่าน/เขียน [PresetColor](../../com.aspose.slides/presetcolor).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public final int getSystemColor()
```

คืนค่า หรือกำหนดสีที่ระบุโดยตารางสีระบบ. อ่าน/เขียน [SystemColor](../../com.aspose.slides/systemcolor).

**คืนค่า:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public final void setSystemColor(int value)
```

คืนค่า หรือกำหนดสีที่ระบุโดยตารางสีระบบ. อ่าน/เขียน [SystemColor](../../com.aspose.slides/systemcolor).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public final int getSchemeColor()
```

คืนค่า หรือกำหนดสีที่ระบุโดยชุดสี. อ่าน/เขียน [SchemeColor](../../com.aspose.slides/schemecolor).

**คืนค่า:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public final void setSchemeColor(int value)
```

คืนค่า หรือกำหนดสีที่ระบุโดยชุดสี. อ่าน/เขียน [SchemeColor](../../com.aspose.slides/schemecolor).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public final byte getR()
```

คืนค่า หรือกำหนดส่วนสีแดงของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  byte .

**คืนค่า:**
byte

### setR(byte value) {#setR-byte-}
```
public final void setR(byte value)
```

คืนค่า หรือกำหนดส่วนสีแดงของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  byte .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public final byte getG()
```

คืนค่า หรือกำหนดส่วนสีเขียวของสี. การแปลงสีทั้งหมดจะถูกละเว้น.

**คืนค่า:**
byte

### setG(byte value) {#setG-byte-}
```
public final void setG(byte value)
```

คืนค่า หรือกำหนดส่วนสีเขียวของสี. การแปลงสีทั้งหมดจะถูกละเว้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public final byte getB()
```

คืนค่า หรือกำหนดส่วนสีน้ำเงินของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  byte .

**คืนค่า:**
byte

### setB(byte value) {#setB-byte-}
```
public final void setB(byte value)
```

คืนค่า หรือกำหนดส่วนสีน้ำเงินของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  byte .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public final float getFloatR()
```

คืนค่า หรือกำหนดส่วนสีแดงของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**คืนค่า:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public final void setFloatR(float value)
```

คืนค่า หรือกำหนดส่วนสีแดงของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public final float getFloatG()
```

คืนค่า หรือกำหนดส่วนสีเขียวของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**คืนค่า:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public final void setFloatG(float value)
```

คืนค่า หรือกำหนดส่วนสีเขียวของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public final float getFloatB()
```

คืนค่า หรือกำหนดส่วนสีน้ำเงินของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**คืนค่า:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public final void setFloatB(float value)
```

คืนค่า หรือกำหนดส่วนสีน้ำเงินของสี. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public final float getHue()
```

คืนค่า หรือกำหนดส่วน hue ของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**คืนค่า:**
float

### setHue(float value) {#setHue-float-}
```
public final void setHue(float value)
```

คืนค่า หรือกำหนดส่วน hue ของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```

คืนค่า หรือกำหนดส่วนความอิ่มของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**คืนค่า:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public final void setSaturation(float value)
```

คืนค่า หรือกำหนดส่วนความอิ่มของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public final float getLuminance()
```

คืนค่า หรือกำหนดส่วนความสว่างของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**คืนค่า:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public final void setLuminance(float value)
```

คืนค่า หรือกำหนดส่วนความสว่างของสีในรูปแบบ HSL. การแปลงสีทั้งหมดจะถูกละเว้น. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public final IColorOperationCollection getColorTransform()
```

คืนคอลเลกชันของการแปลงสีที่นำไปใช้กับสี. อ่านอย่างเดียว [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

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

ตรวจสอบความเท่ากันกับอ็อบเจกต์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | Object. |

**คืนค่า:**
boolean - true หากอ็อบเจกต์เท่ากัน, มิฉะนั้น false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

คืนค่า hash code.

**คืนค่า:**
int - แฮชโค้ด.

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

คืนค่า พาเรนท์ IPresentationComponent. อ่านอย่างเดียว [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**คืนค่า:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)