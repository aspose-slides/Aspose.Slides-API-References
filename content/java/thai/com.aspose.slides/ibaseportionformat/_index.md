---
title: IBasePortionFormat
second_title: Aspose.Slides for Java API Reference
description: This class contains the text portion formatting properties.
type: docs
url: /th/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนข้อความทั้งหมด. แตกต่างจาก [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.

--------------------

คลาสนี้ใช้สำหรับคืนค่าและจัดการคุณสมบัติการจัดรูปแบบส่วนข้อความที่กำหนดสำหรับส่วนเฉพาะ. นี้หมายความว่าไม่มีการสืบทอดเมื่อดึงค่าจึงในกรณีส่วนใหญ่คุณจะได้รับค่าที่หมายถึง “ไม่กำหนด”.

เพื่อรับค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงที่สืบทอด คุณต้องใช้เมธอด [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) ซึ่งจะคืนค่าอินสแตนซ์ของ [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | คืนค่า property LineFormat สำหรับการร่างกรอบข้อความ. |
| [getFillFormat()](#getFillFormat--) | คืนค่า property FillFormat ของข้อความ. |
| [getEffectFormat()](#getEffectFormat--) | คืนค่า property EffectFormat ของข้อความ. |
| [getHighlightColor()](#getHighlightColor--) | คืนค่าสีที่ใช้ไฮไลท์ข้อความ. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | คืนค่า property LineFormat ที่ใช้ร่างเส้นขีดใต้. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | คืนค่า property FillFormat ของเส้นขีดใต้. |
| [getFontBold()](#getFontBold--) | กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่. |
| [setFontBold(byte value)](#setFontBold-byte-) | กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่. |
| [getFontItalic()](#getFontItalic--) | กำหนดว่าแบบอักษรเป็นตัวเอียงหรือไม่. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | กำหนดว่าแบบอักษรเป็นตัวเอียงหรือไม่. |
| [getKumimoji()](#getKumimoji--) | กำหนดว่าตัวเลขควรละเลยการจัดวางข้อความแนวตั้งตามภาษาตะวันออกหรือไม่. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | กำหนดว่าตัวเลขควรละเลยการจัดวางข้อความแนวตั้งตามภาษาตะวันออกหรือไม่. |
| [getNormaliseHeight()](#getNormaliseHeight--) | กำหนดว่าความสูงของข้อความควรทำให้เป็นแบบมาตรฐานหรือไม่. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | กำหนดว่าความสูงของข้อความควรทำให้เป็นแบบมาตรฐานหรือไม่. |
| [getProofDisabled()](#getProofDisabled--) | กำหนดว่าข้อความไม่ควรตรวจสอบการพิสูจน์หรือไม่. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | กำหนดว่าข้อความไม่ควรตรวจสอบการพิสูจน์หรือไม่. |
| [getFontUnderline()](#getFontUnderline--) | คืนค่า หรือกำหนดประเภทการขีดเส้นใต้ของข้อความ. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | คืนค่า หรือกำหนดประเภทการขีดเส้นใต้ของข้อความ. |
| [getTextCapType()](#getTextCapType--) | คืนค่า หรือกำหนดประเภทของการใช้ตัวพิมพ์ใหญ่ของข้อความ. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | คืนค่า หรือกำหนดประเภทของการใช้ตัวพิมพ์ใหญ่ของข้อความ. |
| [getStrikethroughType()](#getStrikethroughType--) | คืนค่า หรือกำหนดประเภทการขีดเส้นคั่นของข้อความ. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | คืนค่า หรือกำหนดประเภทการขีดเส้นคั่นของข้อความ. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | กำหนดว่ารูปแบบขีดเส้นใต้มี property LineFormat ของตนเองหรือสืบทอดจาก property LineFormat ของข้อความ. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | กำหนดว่ารูปแบบขีดเส้นใต้มี property LineFormat ของตนเองหรือสืบทอดจาก property LineFormat ของข้อความ. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | กำหนดว่ารูปแบบขีดเส้นใต้มี property FillFormat ของตนเองหรือสืบทอดจาก property FillFormat ของข้อความ. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | กำหนดว่ารูปแบบขีดเส้นใต้มี property FillFormat ของตนเองหรือสืบทอดจาก property FillFormat ของข้อความ. |
| [getFontHeight()](#getFontHeight--) | คืนค่า หรือกำหนดความสูงของแบบอักษรของส่วน. |
| [setFontHeight(float value)](#setFontHeight-float-) | คืนค่า หรือกำหนดความสูงของแบบอักษรของส่วน. |
| [getLatinFont()](#getLatinFont--) | คืนค่า หรือกำหนดข้อมูลแบบอักษรละติน. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | คืนค่า หรือกำหนดข้อมูลแบบอักษรละติน. |
| [getEastAsianFont()](#getEastAsianFont--) | คืนค่า หรือกำหนดข้อมูลแบบอักษรเอเชียตะวันออก. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | คืนค่า หรือกำหนดข้อมูลแบบอักษรเอเชียตะวันออก. |
| [getComplexScriptFont()](#getComplexScriptFont--) | คืนค่า หรือกำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | คืนค่า หรือกำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน. |
| [getSymbolFont()](#getSymbolFont--) | คืนค่า หรือกำหนดข้อมูลแบบอักษรสัญลักษณ์. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | คืนค่า หรือกำหนดข้อมูลแบบอักษรสัญลักษณ์. |
| [getEscapement()](#getEscapement--) | คืนค่า หรือกำหนดข้อความซูเปอร์สคริปต์หรือซับสคริปต์. |
| [setEscapement(float value)](#setEscapement-float-) | คืนค่า หรือกำหนดข้อความซูเปอร์สคริปต์หรือซับสคริปต์. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | คืนค่า หรือกำหนดขนาดแบบอักษรขั้นต่ำที่ต้องเปิดการ kernning. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | คืนค่า หรือกำหนดขนาดแบบอักษรขั้นต่ำที่ต้องเปิดการ kernning. |
| [getLanguageId()](#getLanguageId--) | คืนค่า หรือกำหนด Id ของภาษาตรวจสอบ. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | คืนค่า หรือกำหนด Id ของภาษาตรวจสอบ. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | คืนค่า หรือกำหนด Id ของภาษาทดแทน. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | คืนค่า หรือกำหนด Id ของภาษาทดแทน. |
| [getSpacing()](#getSpacing--) | คืนค่า หรือกำหนดการเพิ่มระยะห่างระหว่างอักขระ. |
| [setSpacing(float value)](#setSpacing-float-) | คืนค่า หรือกำหนดการเพิ่มระยะห่างระหว่างอักขระ. |
| [getSpellCheck()](#getSpellCheck--) | รับ หรือกำหนดค่าที่บ่งชี้ว่าการตรวจสอบการสะกดเปิดสำหรับส่วนข้อความหรือไม่. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | รับ หรือกำหนดค่าที่บ่งชี้ว่าการตรวจสอบการสะกดเปิดสำหรับส่วนข้อความหรือไม่. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

คืนค่า property LineFormat สำหรับการร่างกรอบข้อความ. ไม่มีการสืบทอด. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

คืนค่า property FillFormat ของข้อความ. ไม่มีการสืบทอด. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

คืนค่า property EffectFormat ของข้อความ. ไม่มีการสืบทอด. อ่านอย่างเดียว [IEffectFormat](../../com.aspose.slides/ieffectformat).

**คืนค่า:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

คืนค่าสีที่ใช้ไฮไลท์ข้อความ. ไม่มีการสืบทอด. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

คืนค่า property LineFormat ที่ใช้ร่างเส้นขีดใต้. ไม่มีการสืบทอด. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

คืนค่า property FillFormat ของเส้นขีดใต้. ไม่มีการสืบทอด. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | byte |  |
### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

กำหนดว่าแบบอักษรเป็นตัวเอียงหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

กำหนดว่าแบบอักษรเป็นตัวเอียงหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | byte |  |
### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

กำหนดว่าตัวเลขควรละเลยการจัดวางข้อความแนวตั้งตามภาษาตะวันออกหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

กำหนดว่าตัวเลขควรละเลยการจัดวางข้อความแนวตั้งตามภาษาตะวันออกหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | byte |  |
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

กำหนดว่าความสูงของข้อความควรทำให้เป็นแบบมาตรฐานหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

กำหนดว่าความสูงของข้อความควรทำให้เป็นแบบมาตรฐานหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | byte |  |
### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

กำหนดว่าข้อความไม่ควรตรวจสอบการพิสูจน์หรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

กำหนดว่าข้อความไม่ควรตรวจสอบการพิสูจน์หรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | byte |  |
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

คืนค่า หรือกำหนดประเภทการขีดเส้นใต้ของข้อความ. ไม่มีการสืบทอด. อ่าน/เขียน [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**คืนค่า:**
byte
### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

คืนค่า หรือกำหนดประเภทการขีดเส้นใต้ของข้อความ. ไม่มีการสืบทอด. อ่าน/เขียน [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | byte |  |
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

คืนค่า หรือกำหนดประเภทของการใช้ตัวพิมพ์ใหญ่ของข้อความ. ไม่มีการสืบทอด. อ่าน/เขียน [TextCapType](../../com.aspose.slides/textcaptype).

**คืนค่า:**
byte
### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

คืนค่า หรือกำหนดประเภทของการใช้ตัวพิมพ์ใหญ่ของข้อความ. ไม่มีการสืบทอด. อ่าน/เขียน [TextCapType](../../com.aspose.slides/textcaptype).

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | byte |  |
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

คืนค่า หรือกำหนดประเภทการขีดเส้นคั่นของข้อความ. ไม่มีการสืบทอด. อ่าน/เขียน [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**คืนค่า:**
byte
### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

คืนค่า หรือกำหนดประเภทการขีดเส้นคั่นของข้อความ. ไม่มีการสืบทอด. อ่าน/เขียน [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

กำหนดว่ารูปแบบขีดเส้นใต้มี property LineFormat ของตนเองหรือสืบทอดจาก property LineFormat ของข้อความ. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

กำหนดว่ารูปแบบขีดเส้นใต้มี property LineFormat ของตนเองหรือสืบทอดจาก property LineFormat ของข้อความ. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

กำหนดว่ารูปแบบขีดเส้นใต้มี property FillFormat ของตนเองหรือสืบทอดจาก property FillFormat ของข้อความ. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

กำหนดว่ารูปแบบขีดเส้นใต้มี property FillFormat ของตนเองหรือสืบทอดจาก property FillFormat ของข้อความ. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | byte |  |
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

คืนค่า หรือกำหนดความสูงของแบบอักษรของส่วน. **Float.NaN** หมายความว่าความสูงไม่กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน float.

**คืนค่า:**
float
### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

คืนค่า หรือกำหนดความสูงของแบบอักษรของส่วน. **Float.NaN** หมายความว่าความสูงไม่กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน float.

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | float |  |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

คืนค่า หรือกำหนดข้อมูลแบบอักษรละติน. Null หมายความว่าแบบอักษรไม่กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

คืนค่า หรือกำหนดข้อมูลแบบอักษรละติน. Null หมายความว่าแบบอักษรไม่กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

คืนค่า หรือกำหนดข้อมูลแบบอักษรเอเชียตะวันออก. Null หมายความว่าแบบอักษรไม่กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

คืนค่า หรือกำหนดข้อมูลแบบอักษรเอเชียตะวันออก. Null หมายความว่าแบบอักษรไม่กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

คืนค่า หรือกำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน. Null หมายความว่าแบบอักษรไม่กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

คืนค่า หรือกำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน. Null หมายความว่าแบบอักษรไม่กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

คืนค่า หรือกำหนดข้อมูลแบบอักษรสัญลักษณ์. Null หมายความว่าแบบอักษรไม่กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

คืนค่า หรือกำหนดข้อมูลแบบอักษรสัญลักษณ์. Null หมายความว่าแบบอักษรไม่กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

คืนค่า หรือกำหนดข้อความซูเปอร์สคริปต์หรือซับสคริปต์. ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซูเปอร์สคริปต์). **Float.NaN** หมายความว่าค่าไม่กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน float.

**คืนค่า:**
float
### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

คืนค่า หรือกำหนดข้อความซูเปอร์สคริปต์หรือซับสคริปต์. ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซูเปอร์สคริปต์). **Float.NaN** หมายความว่าค่าไม่กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน float.

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | float |  |
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

คืนค่า หรือกำหนดขนาดแบบอักษรขั้นต่ำที่ต้องเปิดการ kernning. **Float.NaN** หมายความว่าค่าไม่กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน float.

**คืนค่า:**
float
### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

คืนค่า หรือกำหนดขนาดแบบอักษรขั้นต่ำที่ต้องเปิดการ kernning. **Float.NaN** หมายความว่าค่าไม่กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน float.

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | float |  |
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

คืนค่า หรือกำหนด Id ของภาษาตรวจสอบ. ใช้สำหรับการตรวจสอบการสะกดและไวยากรณ์. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

คืนค่า หรือกำหนด Id ของภาษาตรวจสอบ. ใช้สำหรับการตรวจสอบการสะกดและไวยากรณ์. อ่าน/เขียน String.

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | java.lang.String |  |
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

คืนค่า หรือกำหนด Id ของภาษาทดแทน. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

คืนค่า หรือกำหนด Id ของภาษาทดแทน. อ่าน/เขียน String.

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | java.lang.String |  |
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

คืนค่า หรือกำหนดการเพิ่มระยะห่างระหว่างอักขระ. **Float.NaN** หมายความว่าค่าไม่กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน float.

**คืนค่า:**
float
### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

คืนค่า หรือกำหนดการเพิ่มระยะห่างระหว่างอักขระ. **Float.NaN** หมายความว่าค่าไม่กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน float.

**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | float |  |
### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

รับ หรือกำหนดค่าที่บ่งชี้ว่าการตรวจสอบการสะกดเปิดสำหรับส่วนข้อความหรือไม่. เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกระงับ. เมื่อตั้งค่าเป็น true การตรวจสอบการสะกดจะได้รับอนุญาต. ค่าเริ่มต้นคือ false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // เข้าถึงส่วนข้อความแรกภายในรูปร่างแรกในสไลด์แรก
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


**คืนค่า:** boolean
### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

รับ หรือกำหนดค่าที่บ่งชี้ว่าการตรวจสอบการสะกดเปิดสำหรับส่วนข้อความหรือไม่. เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกระงับ. เมื่อตั้งค่าเป็น true การตรวจสอบการสะกดจะได้รับอนุญาต. ค่าเริ่มต้นคือ false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // เข้าถึงส่วนข้อความแรกภายในรูปร่างแรกในสไลด์แรก
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


**พารามิเตอร์** | **ประเภท** | **คำอธิบาย**
| --- | --- | --- |
| value | boolean |  |