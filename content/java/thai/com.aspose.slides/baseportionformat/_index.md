---
title: BasePortionFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: คุณสมบัติการจัดรูปแบบส่วนข้อความทั่วไป.
type: docs
url: /th/com.aspose.slides/baseportionformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

คุณลักษณะการจัดรูปแบบส่วนข้อความทั่วไป.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | คืนค่า property ของ LineFormat สำหรับการทำขอบข้อความ. |
| [getFillFormat()](#getFillFormat--) | คืนค่า property ของ FillFormat ของข้อความ. |
| [getEffectFormat()](#getEffectFormat--) | คืนค่า property ของ EffectFormat ของข้อความ. |
| [getHighlightColor()](#getHighlightColor--) | คืนค่าสีที่ใช้ไฮไลท์ข้อความ. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | คืนค่า property ของ LineFormat ที่ใช้ทำขอบเส้นขีดเส้นใต้. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | คืนค่า property ของ FillFormat ของเส้นขีดเส้นใต้. |
| [getFontBold()](#getFontBold--) | ระบุว่าฟอนท์เป็นแบบตัวหนาหรือไม่. |
| [setFontBold(byte value)](#setFontBold-byte-) | ระบุว่าฟอนท์เป็นแบบตัวหนาหรือไม่. |
| [getFontItalic()](#getFontItalic--) | ระบุว่าฟอนท์เป็นแบบตัวเอียงหรือไม่. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | ระบุว่าฟอนท์เป็นแบบตัวเอียงหรือไม่. |
| [getKumimoji()](#getKumimoji--) | ระบุว่าตัวเลขควรละเว้นการจัดแนวข้อความแนวตั้งตามภาษาตะวันออกหรือไม่. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | ระบุว่าตัวเลขควรละเว้นการจัดแนวข้อความแนวตั้งตามภาษาตะวันออกหรือไม่. |
| [getNormaliseHeight()](#getNormaliseHeight--) | ระบุว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | ระบุว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. |
| [getProofDisabled()](#getProofDisabled--) | ระบุว่าข้อความไม่ควรตรวจสอบการสะกดหรือไม่. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | ระบุว่าข้อความไม่ควรตรวจสอบการสะกดหรือไม่. |
| [getFontUnderline()](#getFontUnderline--) | คืนค่า หรือกำหนดประเภทการขีดเส้นใต้ของข้อความ. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | คืนค่า หรือกำหนดประเภทการขีดเส้นใต้ของข้อความ. |
| [getTextCapType()](#getTextCapType--) | คืนค่า หรือกำหนดประเภทการพิมพ์ใหญ่ของข้อความ. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | คืนค่า หรือกำหนดประเภทการพิมพ์ใหญ่ของข้อความ. |
| [getStrikethroughType()](#getStrikethroughType--) | คืนค่า หรือกำหนดประเภทการขีดฆ่าของข้อความ. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | คืนค่า หรือกำหนดประเภทการขีดฆ่าของข้อความ. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | ระบุว่ารูปแบบขีดเส้นใต้มี property ของ LineFormat ของตัวเองหรือสืบทอดจาก property ของ LineFormat ของข้อความ. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | ระบุว่ารูปแบบขีดเส้นใต้มี property ของ LineFormat ของตัวเองหรือสืบทอดจาก property ของ LineFormat ของข้อความ. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | ระบุว่ารูปแบบขีดเส้นใต้มี property ของ FillFormat ของตัวเองหรือสืบทอดจาก property ของ FillFormat ของข้อความ. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | ระบุว่ารูปแบบขีดเส้นใต้มี property ของ FillFormat ของตัวเองหรือสืบทอดจาก property ของ FillFormat ของข้อความ. |
| [getFontHeight()](#getFontHeight--) | คืนค่า หรือกำหนดความสูงของฟอนท์ของส่วนข้อความ. |
| [setFontHeight(float value)](#setFontHeight-float-) | คืนค่า หรือกำหนดความสูงของฟอนท์ของส่วนข้อความ. |
| [getLatinFont()](#getLatinFont--) | คืนค่า หรือกำหนดข้อมูลฟอนท์ภาษาและติน. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | คืนค่า หรือกำหนดข้อมูลฟอนท์ภาษาและติน. |
| [getEastAsianFont()](#getEastAsianFont--) | คืนค่า 또는กำหนดข้อมูลฟอนท์ภาษาตะวันออกเอเชีย. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | คืนค่า หรือกำหนดข้อมูลฟอนท์ภาษาตะวันออกเอเชีย. |
| [getComplexScriptFont()](#getComplexScriptFont--) | คืนค่า หรือกำหนดข้อมูลฟอนท์สคริปต์ซับซ้อน. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | คืนค่า หรือกำหนดข้อมูลฟอนท์สคริปต์ซับซ้อน. |
| [getSymbolFont()](#getSymbolFont--) | คืนค่า หรือกำหนดข้อมูลฟอนท์สัญลักษณ์. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | คืนค่า หรือกำหนดข้อมูลฟอนท์สัญลักษณ์. |
| [getEscapement()](#getEscapement--) | คืนค่า หรือกำหนดข้อความเป็นซูเปอร์สคริปต์หรือซับสคริปต์. |
| [setEscapement(float value)](#setEscapement-float-) | คืนค่า หรือกำหนดข้อความเป็นซูเปอร์สคริปต์หรือซับสคริปต์. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | คืนค่า หรือกำหนดขนาดฟอนท์ขั้นต่ำที่ต้องเปิดการเคอร์นนิง. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | คืนค่า หรือกำหนดขนาดฟอนท์ขั้นต่ำที่ต้องเปิดการเคอร์นนิง. |
| [getLanguageId()](#getLanguageId--) | คืนค่า หรือกำหนด Id ของภาษาการตรวจสอบ. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | คืนค่า หรือกำหนด Id ของภาษาการตรวจสอบ. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | คืนค่า หรือกำหนด Id ของภาษาทางเลือก. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | คืนค่า หรือกำหนด Id ของภาษาทางเลือก. |
| [getSpacing()](#getSpacing--) | คืนค่า หรือกำหนดการเพิ่มช่องว่างระหว่างตัวอักษร. |
| [setSpacing(float value)](#setSpacing-float-) | คืนค่า หรือกำหนดการเพิ่มช่องว่างระหว่างตัวอักษร. |
| [getSpellCheck()](#getSpellCheck--) | รับหรือกำหนดค่าส่งสัญญาณว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนของข้อความหรือไม่. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | รับหรือกำหนดค่าส่งสัญญาณว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนของข้อความหรือไม่. |

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

คืนค่า property ของ LineFormat สำหรับการทำขอบข้อความ. ไม่มีการสืบทอด. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

คืนค่า property ของ FillFormat ของข้อความ. ไม่มีการสืบทอด. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

คืนค่า property ของ EffectFormat ของข้อความ. ไม่มีการสืบทอด. อ่านอย่างเดียว [IEffectFormat](../../com.aspose.slides/ieffectformat).

**คืนค่า:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

คืนค่าสีที่ใช้ไฮไลท์ข้อความ. ไม่มีการสืบทอด. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

คืนค่า property ของ LineFormat ที่ใช้ทำขอบเส้นขีดเส้นใต้. ไม่มีการสืบทอด. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

คืนค่า property ของ FillFormat ของเส้นขีดเส้นใต้. ไม่มีการสืบทอด. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

ระบุว่าฟอนท์เป็นแบบตัวหนาหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

ระบุว่าฟอนท์เป็นแบบตัวหนาหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

ระบุว่าฟอนท์เป็นแบบตัวเอียงหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

ระบุว่าฟอนท์เป็นแบบตัวเอียงหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

ระบุว่าตัวเลขควรละเว้นการจัดแนวข้อความแนวตั้งตามภาษาตะวันออกหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

ระบุว่าตัวเลขควรละเว้นการจัดแนวข้อความแนวตั้งตามภาษาตะวันออกหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

ระบุว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

ระบุว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

ระบุว่าข้อความไม่ควรตรวจสอบการสะกดหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

ระบุว่าข้อความไม่ควรตรวจสอบการสะกดหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

คืนค่า หรือกำหนดประเภทการขีดเส้นใต้ของข้อความ. ไม่มีการสืบทอด. อ่าน/เขียน [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**คืนค่า:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

คืนค่า หรือกำหนดประเภทการขีดเส้นใต้ของข้อความ. ไม่มีการสืบทอด. อ่าน/เขียน [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

คืนค่า หรือกำหนดประเภทการพิมพ์ใหญ่ของข้อความ. ไม่มีการสืบทอด. อ่าน/เขียน [TextCapType](../../com.aspose.slides/textcaptype).

**คืนค่า:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

คืนค่า หรือกำหนดประเภทการพิมพ์ใหญ่ของข้อความ. ไม่มีการสืบทอด. อ่าน/เขียน [TextCapType](../../com.aspose.slides/textcaptype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

คืนค่า หรือกำหนดประเภทการขีดฆ่าของข้อความ. ไม่มีการสืบทอด. อ่าน/เขียน [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**คืนค่า:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```
คืนหรือกำหนดประเภทการขีดเส้นผ่านกลางของข้อความ ไม่ได้ใช้การสืบทอด อ่าน/เขียน [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

กำหนดว่ารูปแบบการขีดเส้นมีคุณสมบัติ LineFormat ของตนเองหรือสืบทอดจากคุณสมบัติ LineFormat ของข้อความหรือไม่ อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

กำหนดว่ารูปแบบการขีดเส้นมีคุณสมบัติ LineFormat ของตนเองหรือสืบทอดจากคุณสมบัติ LineFormat ของข้อความหรือไม่ อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

กำหนดว่ารูปแบบการขีดเส้นมีคุณสมบัติ FillFormat ของตนเองหรือสืบทอดจากคุณสมบัติ FillFormat ของข้อความหรือไม่ อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

กำหนดว่ารูปแบบการขีดเส้นมีคุณสมบัติ FillFormat ของตนเองหรือสืบทอดจากคุณสมบัติ FillFormat ของข้อความหรือไม่ อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

คืนหรือกำหนดความสูงของแบบอักษรของส่วนหนึ่ง **Float.NaN** หมายถึงความสูงไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน  float .

**คืนค่า:**
float
### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

คืนหรือกำหนดความสูงของแบบอักษรของส่วนหนึ่ง **Float.NaN** หมายถึงความสูงไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

คืนหรือกำหนดข้อมูลแบบอักษร Latin Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

คืนหรือกำหนดข้อมูลแบบอักษร Latin Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

คืนหรือกำหนดข้อมูลแบบอักษร East Asian Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

คืนหรือกำหนดข้อมูลแบบอักษร East Asian Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

คืนหรือกำหนดข้อมูลแบบอักษร complex script Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

คืนหรือกำหนดข้อมูลแบบอักษร complex script Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

คืนหรือกำหนดข้อมูลแบบอักษร symbolic Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

คืนหรือกำหนดข้อมูลแบบอักษร symbolic Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

คืนหรือกำหนดข้อความซูพอร์สคริปต์หรือซับสคริปต์ ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซูพอร์สคริปต์) **Float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน  float .

**คืนค่า:**
float
### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

คืนหรือกำหนดข้อความซูพอร์สคริปต์หรือซับสคริปต์ ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซูพอร์สคริปต์) **Float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

คืนหรือกำหนดขนาดแบบอักษรต่ำสุดที่ควรเปิดใช้งาน kerning **Float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน  float .

**คืนค่า:**
float
### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

คืนหรือกำหนดขนาดแบบอักษรต่ำสุดที่ควรเปิดใช้งาน kerning **Float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

คืนหรือกำหนด Id ของภาษาตรวจสอบการพิมพ์ ใช้สำหรับตรวจสอบการสะกดและไวยากรณ์ อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

คืนหรือกำหนด Id ของภาษาตรวจสอบการพิมพ์ ใช้สำหรับตรวจสอบการสะกดและไวยากรณ์ อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

คืนหรือกำหนด Id ของภาษาทางเลือกอื่น อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

คืนหรือกำหนด Id ของภาษาทางเลือกอื่น อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

คืนหรือกำหนดการเพิ่มระยะห่างระหว่างอักขระ **Float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน  float .

**คืนค่า:**
float
### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

คืนหรือกำหนดการเพิ่มระยะห่างระหว่างอักขระ **Float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

รับหรือกำหนดค่าที่บ่งบอกว่าการตรวจสอบการสะกดถูกเปิดใช้งานสำหรับส่วนของข้อความหรือไม่ เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกยับยั้ง เมื่อตั้งค่าเป็น true การตรวจสอบการสะกดจะถูกอนุญาต ค่าเริ่มต้นคือ  false .

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // เข้าถึงส่วนแรกของข้อความภายในรูปร่างแรกบนสไลด์แรก
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // เปิดการตรวจสอบการสะกดสำหรับส่วนข้อความนี้
>      portion.getPortionFormat().setSpellCheck(true);
>      // บันทึกการนำเสนอที่แก้ไขแล้ว
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

รับหรือกำหนดค่าที่บ่งบอกว่าการตรวจสอบการสะกดถูกเปิดใช้งานสำหรับส่วนของข้อความหรือไม่ เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกยับยั้ง เมื่อตั้งค่าเป็น true การตรวจสอบการสะกดจะถูกอนุญาต ค่าเริ่มต้นคือ  false .

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // เข้าถึงส่วนแรกของข้อความภายในรูปร่างแรกบนสไลด์แรก
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // เปิดการตรวจสอบการสะกดสำหรับส่วนข้อความนี้
>      portion.getPortionFormat().setSpellCheck(true);
>      // บันทึกการนำเสนอที่ถูกแก้ไข
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |