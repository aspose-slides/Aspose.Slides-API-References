---
title: BasePortionFormat
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: คุณสมบัติการจัดรูปแบบส่วนข้อความทั่วไป
type: docs
url: /th/com.aspose.slides/baseportionformat/
---
**สืบทอด:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**  
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)  
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

Common text portion formatting properties.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | คืนค่าแอตทริบิวต์ LineFormat สำหรับการกำหนดแนวขอบข้อความ. |
| [getFillFormat()](#getFillFormat--) | คืนค่าแอตทริบิวต์ FillFormat ของข้อความ. |
| [getEffectFormat()](#getEffectFormat--) | คืนค่าแอตทริบิวต์ EffectFormat ของข้อความ. |
| [getHighlightColor()](#getHighlightColor--) | คืนค่าสีที่ใช้ไฮไลต์ข้อความ. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | คืนค่าแอตทริบิวต์ LineFormat ที่ใช้กำหนดแนวขอบเส้นขีดเส้นใต้. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | คืนค่าแอตทริบิวต์ FillFormat ของเส้นขีดเส้นใต้. |
| [getFontBold()](#getFontBold--) | ตรวจสอบว่าแบบอักษรเป็นตัวหนาหรือไม่. |
| [setFontBold(byte value)](#setFontBold-byte-) | ตรวจสอบว่าแบบอักษรเป็นตัวหนาหรือไม่. |
| [getFontItalic()](#getFontItalic--) | ตรวจสอบว่าแบบอักษรเป็นตัวเอียงหรือไม่. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | ตรวจสอบว่าแบบอักษรเป็นตัวเอียงหรือไม่. |
| [getKumimoji()](#getKumimoji--) | ตรวจสอบว่าตัวเลขควรละเว้นการจัดแนวข้อความตามแนวตั้งของภาษาตะวันออกหรือไม่. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | ตรวจสอบว่าตัวเลขควรละเว้นการจัดแนวข้อความตามแนวตั้งของภาษาตะวันออกหรือไม่. |
| [getNormaliseHeight()](#getNormaliseHeight--) | ตรวจสอบว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | ตรวจสอบว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. |
| [getProofDisabled()](#getProofDisabled--) | ตรวจสอบว่าข้อความไม่ควรทำการตรวจสอบหรือไม่. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | ตรวจสอบว่าข้อความไม่ควรทำการตรวจสอบหรือไม่. |
| [getFontUnderline()](#getFontUnderline--) | คืนค่าหรือกำหนดประเภทการขีดเส้นใต้ของข้อความ. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | คืนค่าหรือกำหนดประเภทการขีดเส้นใต้ของข้อความ. |
| [getTextCapType()](#getTextCapType--) | คืนค่าหรือกำหนดประเภทการใช้ตัวพิมพ์ใหญ่ของข้อความ. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | คืนค่าหรือกำหนดประเภทการใช้ตัวพิมพ์ใหญ่ของข้อความ. |
| [getStrikethroughType()](#getStrikethroughType--) | คืนค่าหรือกำหนดประเภทการขีดฆ่าของข้อความ. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | คืนค่าหรือกำหนดประเภทการขีดฆ่าของข้อความ. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | ตรวจสอบว่าสไตล์การขีดเส้นใต้มีแอตทริบิวต์ LineFormat ของตนเองหรือสืบทอดจากแอตทริบิวต์ LineFormat ของข้อความ. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | ตรวจสอบว่าสไตล์การขีดเส้นใต้มีแอตทริบิวต์ LineFormat ของตนเองหรือสืบทอดจากแอตทริบิวต์ LineFormat ของข้อความ. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | ตรวจสอบว่าสไตล์การขีดเส้นใต้มีแอตทริบิวต์ FillFormat ของตนเองหรือสืบทอดจากแอตทริบิวต์ FillFormat ของข้อความ. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | ตรวจสอบว่าสไตล์การขีดเส้นใต้มีแอตทริบิวต์ FillFormat ของตนเองหรือสืบทอดจากแอตทริบิวต์ FillFormat ของข้อความ. |
| [getFontHeight()](#getFontHeight--) | คืนค่าหรือกำหนดความสูงของแบบอักษรของส่วนหนึ่ง. |
| [setFontHeight(float value)](#setFontHeight-float-) | คืนค่าหรือกำหนดความสูงของแบบอักษรของส่วนหนึ่ง. |
| [getLatinFont()](#getLatinFont--) | คืนค่าหรือกำหนดข้อมูลแบบอักษรละติน. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | คืนค่าหรือกำหนดข้อมูลแบบอักษรละติน. |
| [getEastAsianFont()](#getEastAsianFont--) | คืนค่าหรือกำหนดข้อมูลแบบอักษรเอเชียตะวันออก. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | คืนค่าหรือกำหนดข้อมูลแบบอักษรเอเชียตะวันออก. |
| [getComplexScriptFont()](#getComplexScriptFont--) | คืนค่าหรือกำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | คืนค่าหรือกำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน. |
| [getSymbolFont()](#getSymbolFont--) | คืนค่าหรือกำหนดข้อมูลแบบอักษรสัญลักษณ์. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | คืนค่าหรือกำหนดข้อมูลแบบอักษรสัญลักษณ์. |
| [getEscapement()](#getEscapement--) | คืนค่าหรือกำหนดข้อความเป็นตัวยกหรือตัวห้อย. |
| [setEscapement(float value)](#setEscapement-float-) | คืนค่าหรือกำหนดข้อความเป็นตัวยกหรือตัวห้อย. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | คืนค่าหรือกำหนดขนาดแบบอักษรขั้นต่ำที่ต้องเปิดการเคอร์นิ่ง. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | คืนค่าหรือกำหนดขนาดแบบอักษรขั้นต่ำที่ต้องเปิดการเคอร์นิ่ง. |
| [getLanguageId()](#getLanguageId--) | คืนค่าหรือกำหนดรหัสของภาษาตรวจสอบ. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | คืนค่าหรือกำหนดรหัสของภาษาตรวจสอบ. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | คืนค่าหรือกำหนดรหัสของภาษาทดแทน. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | คืนค่าหรือกำหนดรหัสของภาษาทดแทน. |
| [getSpacing()](#getSpacing--) | คืนค่าหรือกำหนดการเพิ่มระยะห่างระหว่างอักขระ. |
| [setSpacing(float value)](#setSpacing-float-) | คืนค่าหรือกำหนดการเพิ่มระยะห่างระหว่างอักขระ. |
| [getSpellCheck()](#getSpellCheck--) | รับหรือกำหนดค่าที่บ่งชี้ว่าการตรวจสอบการสะกดเปิดสำหรับส่วนข้อความหรือไม่. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | รับหรือกำหนดค่าที่บ่งชี้ว่าการตรวจสอบการสะกดเปิดสำหรับส่วนข้อความหรือไม่. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**  
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

คืนค่าแอตทริบิวต์ LineFormat สำหรับการกำหนดแนวขอบข้อความ. ไม่ได้ใช้การสืบทอด. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

คืนค่าแอตทริบิวต์ FillFormat ของข้อความ. ไม่ได้ใช้การสืบทอด. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

คืนค่าแอตทริบิวต์ EffectFormat ของข้อความ. ไม่ได้ใช้การสืบทอด. อ่านอย่างเดียว [IEffectFormat](../../com.aspose.slides/ieffectformat).

**คืนค่า:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

คืนค่าสีที่ใช้ไฮไลต์ข้อความ. ไม่ได้ใช้การสืบทอด. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

คืนค่าแอตทริบิวต์ LineFormat ที่ใช้กำหนดแนวขอบเส้นขีดเส้นใต้. ไม่ได้ใช้การสืบทอด. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

คืนค่าแอตทริบิวต์ FillFormat ของเส้นขีดเส้นใต้. ไม่ได้ใช้การสืบทอด. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

ตรวจสอบว่าแบบอักษรเป็นตัวหนาหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**  
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

ตรวจสอบว่าแบบอักษรเป็นตัวหนาหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

ตรวจสอบว่าแบบอักษรเป็นตัวเอียงหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**  
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

ตรวจสอบว่าแบบอักษรเป็นตัวเอียงหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

ตรวจสอบว่าตัวเลขควรละเว้นการจัดแนวข้อความตามแนวตั้งของภาษาตะวันออกหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**  
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

ตรวจสอบว่าตัวเลขควรละเว้นการจัดแนวข้อความตามแนวตั้งของภาษาตะวันออกหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

ตรวจสอบว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**  
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

ตรวจสอบว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

ตรวจสอบว่าข้อความไม่ควรทำการตรวจสอบหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**  
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

ตรวจสอบว่าข้อความไม่ควรทำการตรวจสอบหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

คืนค่าหรือกำหนดประเภทการขีดเส้นใต้ของข้อความ. ไม่ได้ใช้การสืบทอด. อ่าน/เขียน [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**คืนค่า:**  
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

คืนค่าหรือกำหนดประเภทการขีดเส้นใต้ของข้อความ. ไม่ได้ใช้การสืบทอด. อ่าน/เขียน [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

คืนค่าหรือกำหนดประเภทการใช้ตัวพิมพ์ใหญ่ของข้อความ. ไม่ได้ใช้การสืบทอด. อ่าน/เขียน [TextCapType](../../com.aspose.slides/textcaptype).

**คืนค่า:**  
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

คืนค่าหรือกำหนดประเภทการใช้ตัวพิมพ์ใหญ่ของข้อความ. ไม่ได้ใช้การสืบทอด. อ่าน/เขียน [TextCapType](../../com.aspose.slides/textcaptype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

คืนค่าหรือกำหนดประเภทการขีดฆ่าของข้อความ. ไม่ได้ใช้การสืบทอด. อ่าน/เขียน [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**คืนค่า:**  
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

คืนค่าหรือกำหนดประเภทการขีดฆ่าของข้อความ. ไม่ได้ใช้การสืบทอด. อ่าน/เขียน [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

ตรวจสอบว่าสไตล์การขีดเส้นใต้มีแอตทริบิวต์ LineFormat ของตนเองหรือสืบทอดจากแอตทริบิวต์ LineFormat ของข้อความ. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**  
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

ตรวจสอบว่าสไตล์การขีดเส้นใต้มีแอตทริบิวต์ LineFormat ของตนเองหรือสืบทอดจากแอตทริบิวต์ LineFormat ของข้อความ. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

ตรวจสอบว่าสไตล์การขีดเส้นใต้มีแอตทริบิวต์ FillFormat ของตนเองหรือสืบทอดจากแอตทริบิวต์ FillFormat ของข้อความ. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**  
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

ตรวจสอบว่าสไตล์การขีดเส้นใต้มีแอตทริบิวต์ FillFormat ของตนเองหรือสืบทอดจากแอตทริบิวต์ FillFormat ของข้อความ. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

คืนค่าหรือกำหนดความสูงของแบบอักษรของส่วนหนึ่ง. **Float.NaN** หมายถึงความสูงยังไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน  float .

**คืนค่า:**  
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

คืนค่าหรือกำหนดความสูงของแบบอักษรของส่วนหนึ่ง. **Float.NaN** หมายถึงความสูงยังไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน  float .

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

คืนค่าหรือกำหนดข้อมูลแบบอักษรละติน. Null หมายถึงแบบอักษรยังไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

คืนค่าหรือกำหนดข้อมูลแบบอักษรละติน. Null หมายถึงแบบอักษรยังไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

คืนค่าหรือกำหนดข้อมูลแบบอักษรเอเชียตะวันออก. Null หมายถึงแบบอักษรยังไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

คืนค่าหรือกำหนดข้อมูลแบบอักษรเอเชียตะวันออก. Null หมายถึงแบบอักษรยังไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

คืนค่าหรือกำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน. Null หมายถึงแบบอักษรยังไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

คืนค่าหรือกำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน. Null หมายถึงแบบอักษรยังไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

คืนค่าหรือกำหนดข้อมูลแบบอักษรสัญลักษณ์. Null หมายถึงแบบอักษรยังไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

คืนค่าหรือกำหนดข้อมูลแบบอักษรสัญลักษณ์. Null หมายถึงแบบอักษรยังไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

คืนค่าหรือกำหนดข้อความเป็นตัวยกหรือตัวห้อย. ค่าระหว่าง -100% (ตัวห้อย) ถึง 100% (ตัวยก). **Float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน  float .

**คืนค่า:**  
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

คืนค่าหรือกำหนดข้อความเป็นตัวยกหรือตัวหอย. ค่าระหว่าง -100% (ตัวห้อย) ถึง 100% (ตัวยก). **Float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน  float .

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

คืนค่าหรือกำหนดขนาดแบบอักษรขั้นต่ำที่ต้องเปิดการเคอร์นิ่ง. **Float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน  float .

**คืนค่า:**  
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

คืนค่าหรือกำหนดขนาดแบบอักษรขั้นต่ำที่ต้องเปิดการเคอร์นิ่ง. **Float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน  float .

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

คืนค่าหรือกำหนดรหัสของภาษาตรวจสอบ. ใช้สำหรับตรวจสอบการสะกดและไวยากรณ์. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

คืนค่าหรือกำหนดรหัสของภาษาตรวจสอบ. ใช้สำหรับตรวจสอบการสะกดและไวยากรณ์. อ่าน/เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

คืนค่าหรือกำหนดรหัสของภาษาทดแทน. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

คืนค่าหรือกำหนดรหัสของภาษาทดแทน. อ่าน/เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

คืนค่าหรือกำหนดการเพิ่มระยะห่างระหว่างอักขระ. **Float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน  float .

**คืนค่า:**  
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

คืนค่าหรือกำหนดการเพิ่มระยะห่างระหว่างอักขระ. **Float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน  float .

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

รับหรือกำหนดค่าที่บ่งชี้ว่าการตรวจสอบการสะกดเปิดสำหรับส่วนข้อความหรือไม่. เมื่อค่าตั้งเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกระงับ; เมื่อเป็น true การตรวจสอบการสะกดจะเปิดให้ทำงาน. ค่าเริ่มต้นคือ false.

**คืนค่า:**  
boolean
--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Access the first portion of text inside the first shape on the first slide
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Enable spell checking for this text portion
>      portion.getPortionFormat().setSpellCheck(true);
>      // Save the modified presentation
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**  
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

รับหรือกำหนดค่าที่บ่งชี้ว่าการตรวจสอบการสะกดเปิดสำหรับส่วนข้อความหรือไม่. เมื่อค่าตั้งเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกระงับ; เมื่อเป็น true การตรวจสอบการสะกดจะเปิดให้ทำงาน. ค่าเริ่มต้นคือ false.

**คืนค่า:**  
boolean
--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Access the first portion of text inside the first shape on the first slide
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Enable spell checking for this text portion
>      portion.getPortionFormat().setSpellCheck(true);
>      // Save the modified presentation
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |