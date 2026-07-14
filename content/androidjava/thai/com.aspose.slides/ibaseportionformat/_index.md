---
title: IBasePortionFormat
second_title: Aspose.Slides for Android via Java API Reference
description: คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนข้อความ
type: docs
url: /th/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนข้อความ ไม่เหมือนกับ [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้

--------------------

คลาสนี้ใช้สำหรับคืนค่าและจัดการคุณสมบัติการจัดรูปแบบส่วนข้อความที่กำหนดให้กับส่วนเฉพาะ หมายความว่าไม่มีการสืบทอดเมื่อดึงค่า ดังนั้นในกรณีส่วนใหญ่คุณจะได้รับค่าที่หมายถึง "ไม่ได้กำหนด"

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงค่าที่สืบทอด คุณต้องใช้วิธี [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) ซึ่งคืนค่าเป็นอินสแตนซ์ [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | คืนค่า properties ของ LineFormat สำหรับการทำเส้นขอบข้อความ |
| [getFillFormat()](#getFillFormat--) | คืนค่า properties ของ FillFormat ของข้อความ |
| [getEffectFormat()](#getEffectFormat--) | คืนค่า properties ของ EffectFormat ของข้อความ |
| [getHighlightColor()](#getHighlightColor--) | คืนค่าสีที่ใช้ไฮไลต์ข้อความ |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | คืนค่า properties ของ LineFormat ที่ใช้ในการทำเส้นขีดเส้นใต้ |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | คืนค่า properties ของ FillFormat ของเส้นขีดเส้นใต้ |
| [getFontBold()](#getFontBold--) | กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่ |
| [setFontBold(byte value)](#setFontBold-byte-) | กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่ |
| [getFontItalic()](#getFontItalic--) | กำหนดว่าแบบอักษรเป็นตัวเอียงหรือไม่ |
| [setFontItalic(byte value)](#setFontItalic-byte-) | กำหนดว่าแบบอักษรเป็นตัวเอียงหรือไม่ |
| [getKumimoji()](#getKumimoji--) | กำหนดว่าตัวเลขควรละเว้นการจัดเรียงข้อความแนวตั้งตามภาษาตะวันออกหรือไม่ |
| [setKumimoji(byte value)](#setKumimoji-byte-) | กำหนดว่าตัวเลขควรละเว้นการจัดเรียงข้อความแนวตั้งตามภาษาตะวันออกหรือไม่ |
| [getNormaliseHeight()](#getNormaliseHeight--) | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่ |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่ |
| [getProofDisabled()](#getProofDisabled--) | กำหนดว่าข้อความไม่ควรตรวจสอบทางไวยากรณ์หรือไม่ |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | กำหนดว่าข้อความไม่ควรตรวจสอบทางไวยากรณ์หรือไม่ |
| [getFontUnderline()](#getFontUnderline--) | คืนค่าหรือกำหนดประเภทการขีดเส้นใต้ของข้อความ |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | คืนค่าหรือกำหนดประเภทการขีดเส้นใต้ของข้อความ |
| [getTextCapType()](#getTextCapType--) | คืนค่าหรือกำหนดประเภทการใช้ตัวพิมพ์ใหญ่ของข้อความ |
| [setTextCapType(byte value)](#setTextCapType-byte-) | คืนค่าหรือกำหนดประเภทการใช้ตัวพิมพ์ใหญ่ของข้อความ |
| [getStrikethroughType()](#getStrikethroughType--) | คืนค่า或กำหนดประเภทการขีดไขว้ของข้อความ |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | คืนค่า或กำหนดประเภทการขีดไขว้ของข้อความ |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ LineFormat ของตนเองหรือสืบทอดจากคุณสมบัติ LineFormat ของข้อความ |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ LineFormat ของตนเองหรือสืบทอดจากคุณสมบัติ LineFormat ของข้อความ |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ FillFormat ของตนเองหรือสืบทอดจากคุณสมบัติ FillFormat ของข้อความ |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ FillFormat ของตนเองหรือสืบทอดจากคุณสมบัติ FillFormat ของข้อความ |
| [getFontHeight()](#getFontHeight--) | คืนค่าหรือกำหนดความสูงของแบบอักษรของส่วน |
| [setFontHeight(float value)](#setFontHeight-float-) | คืนค่าหรือกำหนดความสูงของแบบอักษรของส่วน |
| [getLatinFont()](#getLatinFont--) | คืนค่าหรือกำหนดข้อมูลแบบอักษรละติน |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | คืนค่าหรือกำหนดข้อมูลแบบอักษรละติน |
| [getEastAsianFont()](#getEastAsianFont--) | คืนค่าหรือกำหนดข้อมูลแบบอักษรเอเชียตะวันออก |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | คืนค่าหรือกำหนดข้อมูลแบบอักษรเอเชียตะวันออก |
| [getComplexScriptFont()](#getComplexScriptFont--) | คืนค่าหรือกำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | คืนค่าหรือกำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน |
| [getSymbolFont()](#getSymbolFont--) | คืนค่าหรือกำหนดข้อมูลแบบอักษรสัญลักษณ์ |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | คืนค่าหรือกำหนดข้อมูลแบบอักษรสัญลักษณ์ |
| [getEscapement()](#getEscapement--) | คืนค่าหรือกำหนดข้อความซูเปอร์สคริปต์หรือซับสคริปต์ |
| [setEscapement(float value)](#setEscapement-float-) | คืนค่าหรือกำหนดข้อความซูเปอร์สคริปต์หรือซับสคริปต์ |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | คืนค่าหรือกำหนดขนาดแบบอักษรขั้นต่ำ ที่ควรเปิดใช้งานการเคอร์นนิง |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | คืนค่าหรือกำหนดขนาดแบบอักษรขั้นต่ำ ที่ควรเปิดใช้งานการเคอร์นนิง |
| [getLanguageId()](#getLanguageId--) | คืนค่าหรือกำหนด Id ของภาษาตรวจสอบ |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | คืนค่าหรือกำหนด Id ของภาษาตรวจสอบ |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | คืนค่าหรือกำหนด Id ของภาษาทางเลือก |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | คืนค่าหรือกำหนด Id ของภาษาทางเลือก |
| [getSpacing()](#getSpacing--) | คืนค่า或กำหนดการเพิ่มระยะห่างระหว่างตัวอักษร |
| [setSpacing(float value)](#setSpacing-float-) | คืนค่า或กำหนดการเพิ่มระยะห่างระหว่างตัวอักษร |
| [getSpellCheck()](#getSpellCheck--) | รับหรือกำหนดค่าที่บ่งชี้ว่าการตรวจสอบการสะกดคำเปิดใช้งานสำหรับส่วนข้อความหรือไม่ |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | รับหรือกำหนดค่าที่บ่งชี้ว่าการตรวจสอบการสะกดคำเปิดใช้งานสำหรับส่วนข้อความหรือไม่ |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

คืนค่า properties ของ LineFormat สำหรับการทำเส้นขอบข้อความ ไม่ได้สืบทอดค่า อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

คืนค่า properties ของ FillFormat ของข้อความ ไม่ได้สืบทอดค่า อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

คืนค่า properties ของ EffectFormat ของข้อความ ไม่ได้สืบทอดค่า อ่านอย่างเดียว [IEffectFormat](../../com.aspose.slides/ieffectformat).

**คืนค่า:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

คืนค่าสีที่ใช้ไฮไลต์ข้อความ ไม่ได้สืบทอดค่า อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

คืนค่า properties ของ LineFormat ที่ใช้ในการทำเส้นขีดเส้นใต้ ไม่ได้สืบทอดค่า อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

คืนค่า properties ของ FillFormat ของเส้นขีดเส้นใต้ ไม่ได้สืบทอดค่า อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่ ไม่ได้สืบทอดค่า อ่าน/เขียนได้ [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่ ไม่ได้สืบทอดค่า อ่าน/เขียนได้ [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

กำหนดว่าแบบอักษรเป็นตัวเอียงหรือไม่ ไม่ได้สืบทอดค่า อ่าน/เขียนได้ [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

กำหนดว่าแบบอักษรเป็นตัวเอียงหรือไม่ ไม่ได้สืบทอดค่า อ่าน/เขียนได้ [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

กำหนดว่าตัวเลขควรละเว้นการจัดเรียงข้อความแนวตั้งตามภาษาตะวันออกหรือไม่ ไม่ได้สืบทอดค่า อ่าน/เขียนได้ [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

กำหนดว่าตัวเลขควรละเว้นการจัดเรียงข้อความแนวตั้งตามภาษาตะวันออกหรือไม่ ไม่ได้สืบทอดค่า อ่าน/เขียนได้ [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่ ไม่ได้สืบทอดค่า อ่าน/เขียนได้ [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่ ไม่ได้สืบทอดค่า อ่าน/เขียนได้ [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

กำหนดว่าข้อความไม่ควรตรวจสอบทางไวยากรณ์หรือไม่ ไม่ได้สืบทอดค่า อ่าน/เขียนได้ [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

กำหนดว่าข้อความไม่ควรตรวจสอบทางไวยากรณ์หรือไม่ ไม่ได้สืบทอดค่า อ่าน/เขียนได้ [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

คืนค่า或กำหนดประเภทการขีดเส้นใต้ของข้อความ ไม่ได้สืบทอดค่า อ่าน/เขียนได้ [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**คืนค่า:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

คืนค่า或กำหนดประเภทการขีดเส้นใต้ของข้อความ ไม่ได้สืบทอดค่า อ่าน/เขียนได้ [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

คืนค่า或กำหนดประเภทการใช้ตัวพิมพ์ใหญ่ของข้อความ ไม่ได้สืบทอดค่า อ่าน/เขียนได้ [TextCapType](../../com.aspose.slides/textcaptype).

**คืนค่า:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

คืนค่า或กำหนดประเภทการใช้ตัวพิมพ์ใหญ่ของข้อความ ไม่ได้สืบทอดค่า อ่าน/เขียนได้ [TextCapType](../../com.aspose.slides/textcaptype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

คืนค่า或กำหนดประเภทการขีดไขว้ของข้อความ ไม่ได้สืบทอดค่า อ่าน/เขียนได้ [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**คืนค่า:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

คืนค่า或กำหนดประเภทการขีดไขว้ของข้อความ ไม่ได้สืบทอดค่า อ่าน/เขียนได้ [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ LineFormat ของตนเองหรือสืบทอดจากคุณสมบัติ LineFormat ของข้อความ อ่าน/เขียนได้ [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ LineFormat ของตนเองหรือสืบทอดจากคุณสมบัติ LineFormat ของข้อความ อ่าน/เขียนได้ [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ FillFormat ของตนเองหรือสืบทอดจากคุณสมบัติ FillFormat ของข้อความ อ่าน/เขียนได้ [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ FillFormat ของตนเองหรือสืบทอดจากคุณสมบัติ FillFormat ของข้อความ อ่าน/เขียนได้ [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

คืนค่า或กำหนดความสูงของแบบอักษรของส่วน **Float.NaN** หมายถึงความสูงไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียนได้ float.

**คืนค่า:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

คืนค่า或กำหนดความสูงของแบบอักษรของส่วน **Float.NaN** หมายถึงความสูงไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียนได้ float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

คืนค่า或กำหนดข้อมูลแบบอักษรละติน Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียนได้ [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

คืนค่า或กำหนดข้อมูลแบบอักษรละติน Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียนได้ [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

คืนค่า或กำหนดข้อมูลแบบอักษรเอเชียตะวันออก Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียนได้ [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

คืนค่า或กำหนดข้อมูลแบบอักษรเอเชียตะวันออก Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียนได้ [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

คืนค่า或กำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียนได้ [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

คืนค่า或กำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียนได้ [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

คืนค่า或กำหนดข้อมูลแบบอักษรสัญลักษณ์ Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียนได้ [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

คืนค่า或กำหนดข้อมูลแบบอักษรสัญลักษณ์ Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียนได้ [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

คืนค่า或กำหนดข้อความซูเปอร์สคริปต์หรือซับสคริปต์ ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซูเปอร์สคริปต์) **Float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียนได้ float.

**คืนค่า:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

คืนค่า或กำหนดข้อความซูเปอร์สคริปต์หรือซับสคริปต์ ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซูเปอร์สคริปต์) **Float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียนได้ float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

คืนค่า或กำหนดขนาดแบบอักษรขั้นต่ำ ที่ควรเปิดใช้งานการเคอร์นนิง **Float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียนได้ float.

**คืนค่า:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

คืนค่า或กำหนดขนาดแบบอักษรขั้นต่ำ ที่ควรเปิดใช้งานการเคอร์นนิง **Float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียนได้ float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

คืนค่า或กำหนด Id ของภาษาตรวจสอบ ใช้สำหรับการตรวจสอบการสะกดและไวยากรณ์ อ่าน/เขียนได้ String.

**คืนค่า:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

คืนค่า或กำหนด Id ของภาษาตรวจสอบ ใช้สำหรับการตรวจสอบการสะกดและไวยากรณ์ อ่าน/เขียนได้ String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

คืนค่า或กำหนด Id ของภาษาทางเลือก อ่าน/เขียนได้ String.

**คืนค่า:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

คืนค่า或กำหนด Id ของภาษาทางเลือก อ่าน/เขียนได้ String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

คืนค่า或กำหนดการเพิ่มระยะห่างระหว่างตัวอักษร **Float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียนได้ float.

**คืนค่า:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

คืนค่า或กำหนดการเพิ่มระยะห่างระหว่างตัวอักษร **Float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียนได้ float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

รับหรือกำหนดค่าที่บ่งชี้ว่าการตรวจสอบการสะกดคำเปิดใช้งานสำหรับส่วนข้อความหรือไม่ เมื่อค่าคุณสมบัตินี้เป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกระงับ เมื่อเป็น true การตรวจสอบการสะกดจะได้รับอนุญาต ค่าเริ่มต้นคือ false.

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
public abstract void setSpellCheck(boolean value)
```

รับหรือกำหนดค่าที่บ่งชี้ว่าการตรวจสอบการสะกดคำเปิดใช้งานสำหรับส่วนข้อความหรือไม่ เมื่อค่าคุณสมบัตินี้เป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกระงับ เมื่อเป็น true การตรวจสอบการสะกดจะได้รับอนุญาต ค่าเริ่มต้นคือ false.

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


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |