---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: อินเทอร์เฟซฐานสำหรับวัตถุที่ไม่เปลี่ยนแปลงได้ซึ่งมีคุณสมบัติการจัดรูปแบบส่วนข้อความที่มีผลจริง.
type: docs
url: /th/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

อินเทอร์เฟซฐานสำหรับวัตถุที่ไม่เปลี่ยนแปลงได้ซึ่งมีคุณสมบัติการจัดรูปแบบส่วนข้อความที่มีผลจริง.

## เมธอด

| Method | Description |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | คืนค่า LineFormat properties สำหรับการทำเส้นขอบของข้อความ. |
| [getFillFormat()](#getFillFormat--) | คืนค่า FillFormat properties ของข้อความ. |
| [getEffectFormat()](#getEffectFormat--) | คืนค่า EffectFormat properties ของข้อความ. |
| [getHighlightColor()](#getHighlightColor--) | คืนค่าสีที่ใช้ไฮไลท์ข้อความ. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | คืนค่า LineFormat properties ที่ใช้ในการทำเส้นขอบของเส้นขีดเส้นใต้. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | คืนค่า FillFormat properties ของเส้นขีดเส้นใต้. |
| [getFontBold()](#getFontBold--) | กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่. |
| [getFontItalic()](#getFontItalic--) | กำหนดว่าแบบอักษรเป็นแบบเอียงหรือไม่. |
| [getKumimoji()](#getKumimoji--) | กำหนดว่าตัวเลขควรละเว้นการจัดวางข้อความแนวตั้งเฉพาะภาษาตะวันออกหรือไม่. |
| [getNormaliseHeight()](#getNormaliseHeight--) | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. |
| [getProofDisabled()](#getProofDisabled--) | กำหนดว่าข้อความไม่ควรตรวจสอบการพิมพ์หรือไม่. |
| [getFontUnderline()](#getFontUnderline--) | คืนค่า text underline type. |
| [getTextCapType()](#getTextCapType--) | คืนค่า type ของการแปลงตัวอักษรของข้อความ. |
| [getStrikethroughType()](#getStrikethroughType--) | คืนค่า strikethrough type ของข้อความ. |
| [getSmartTagClean()](#getSmartTagClean--) | กำหนดว่าควรทำความสะอาด smart tag หรือไม่. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | กำหนดว่ารูปแบบขีดเส้นใต้มีกำหนด LineFormat properties ของตนเองหรือสืบทอดจาก LineFormat properties ของข้อความ. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | กำหนดว่ารูปแบบขีดเส้นใต้มีกำหนด FillFormat properties ของตนเองหรือสืบทอดจาก FillFormat properties ของข้อความ. |
| [getFontHeight()](#getFontHeight--) | คืนค่าความสูงของแบบอักษรของส่วนข้อความ หน่วยจุด. |
| [getLatinFont()](#getLatinFont--) | คืนค่า Latin font info. |
| [getEastAsianFont()](#getEastAsianFont--) | คืนค่า East Asian font info. |
| [getComplexScriptFont()](#getComplexScriptFont--) | คืนค่า complex script font info. |
| [getSymbolFont()](#getSymbolFont--) | คืนค่า symbolic font info. |
| [getEscapement()](#getEscapement--) | คืนค่าข้อความซูเปอร์สคริปต์หรือซับสคริปต์. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | คืนค่าขนาดแบบอักษรขั้นต่ำที่ควรเปิด kerning. |
| [getLanguageId()](#getLanguageId--) | คืนค่า Id ของภาษา. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | คืนค่า Id ของภาษาทดแทน. |
| [getSpacing()](#getSpacing--) | คืนค่าการเพิ่มระยะห่างระหว่างตัวอักษร หน่วยจุด. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

คืนค่า LineFormat properties สำหรับการทำเส้นขอบของข้อความ. อ่านอย่างเดียว [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**ผลลัพธ์:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

คืนค่า FillFormat properties ของข้อความ. อ่านอย่างเดียว [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**ผลลัพธ์:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

คืนค่า EffectFormat properties ของข้อความ. อ่านอย่างเดียว [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**ผลลัพธ์:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)

### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```

คืนค่าสีที่ใช้ไฮไลท์ข้อความ. อ่านอย่างเดียว java.awt.Color.

**ผลลัพธ์:**
java.awt.Color

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

คืนค่า LineFormat properties ที่ใช้ในการทำเส้นขอบของเส้นขีดเส้นใต้. อ่านอย่างเดียว [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**ผลลัพธ์:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

คืนค่า FillFormat properties ของเส้นขีดเส้นใต้. อ่านอย่างเดียว [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**ผลลัพธ์:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)

### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่. อ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean

### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

กำหนดว่าแบบอักษรเป็นแบบเอียงหรือไม่. อ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean

### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

กำหนดว่าตัวเลขควรละเว้นการจัดวางข้อความแนวตั้งเฉพาะภาษาตะวันออกหรือไม่. อ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. อ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean

### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

กำหนดว่าข้อความไม่ควรตรวจสอบการพิมพ์หรือไม่. อ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

คืนค่า text underline type. อ่านอย่างเดียว [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**ผลลัพธ์:**
byte

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

คืนค่า type ของการแปลงตัวอักษรของข้อความ. อ่านอย่างเดียว [TextCapType](../../com.aspose.slides/textcaptype).

**ผลลัพธ์:**
byte

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

คืนค่า strikethrough type ของข้อความ. อ่านอย่างเดียว [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**ผลลัพธ์:**
byte

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

กำหนดว่าควรทำความสะอาด smart tag หรือไม่. อ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

กำหนดว่ารูปแบบขีดเส้นใต้มีกำหนด LineFormat properties ของตนเองหรือสืบทอดจาก LineFormat properties ของข้อความ. อ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

กำหนดว่ารูปแบบขีดเส้นใต้มีกำหนด FillFormat properties ของตนเองหรือสืบทอดจาก FillFormat properties ของข้อความ. อ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

คืนค่าความสูงของแบบอักษรของส่วนข้อความ หน่วยจุด. อ่านอย่างเดียว float.

**ผลลัพธ์:**
float

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

คืนค่า Latin font info. อ่านอย่างเดียว [IFontData](../../com.aspose.slides/ifontdata).

**ผลลัพธ์:**
[IFontData](../../com.aspose.slides/ifontdata)

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

คืนค่า East Asian font info. อ่านอย่างเดียว [IFontData](../../com.aspose.slides/ifontdata).

**ผลลัพธ์:**
[IFontData](../../com.aspose.slides/ifontdata)

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

คืนค่า complex script font info. อ่านอย่างเดียว [IFontData](../../com.aspose.slides/ifontdata).

**ผลลัพธ์:**
[IFontData](../../com.aspose.slides/ifontdata)

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

คืนค่า symbolic font info. อ่านอย่างเดียว [IFontData](../../com.aspose.slides/ifontdata).

**ผลลัพธ์:**
[IFontData](../../com.aspose.slides/ifontdata)

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

คืนค่าข้อความซูเปอร์สคริปต์หรือซับสคริปต์. ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซูเปอร์สคริปต์). อ่านอย่างเดียว float.

**ผลลัพธ์:**
float

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

คืนค่าขนาดแบบอักษรขั้นต่ำที่ควรเปิด kerning. อ่านอย่างเดียว float.

**ผลลัพธ์:**
float

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

คืนค่า Id ของภาษา. อ่านอย่างเดียว String.

**ผลลัพธ์:**
java.lang.String

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

คืนค่า Id ของภาษาทดแทน. อ่านอย่างเดียว String.

**ผลลัพธ์:**
java.lang.String

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

คืนค่าการเพิ่มระยะห่างระหว่างตัวอักษร หน่วยจุด. อ่านอย่างเดียว float.

**ผลลัพธ์:**
float