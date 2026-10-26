---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: อินเทอร์เฟซพื้นฐานสำหรับอ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งมีคุณลักษณะการจัดรูปแบบส่วนข้อความที่มีผล.
type: docs
url: /th/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

อินเทอร์เฟซพื้นฐานสำหรับอ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งมีคุณลักษณะการจัดรูปแบบส่วนข้อความที่มีผล.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | คืนค่าแอตริบิวต์ LineFormat สำหรับการร่างเส้นขอบข้อความ. |
| [getFillFormat()](#getFillFormat--) | คืนค่าแอตริบิวต์ FillFormat ของข้อความ. |
| [getEffectFormat()](#getEffectFormat--) | คืนค่าแอตริบิวต์ EffectFormat ของข้อความ. |
| [getHighlightColor()](#getHighlightColor--) | คืนค่าสีที่ใช้เน้นข้อความ. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | คืนค่าแอตริบิวต์ LineFormat ที่ใช้ร่างเส้นขอบขีดเส้นใต้. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | คืนค่าแอตริบิวต์ FillFormat ของเส้นขีดใต้. |
| [getFontBold()](#getFontBold--) | กำหนดว่าฟอนต์เป็นตัวหนาหรือไม่. |
| [getFontItalic()](#getFontItalic--) | กำหนดว่าฟอนต์เป็นตัวเอียงหรือไม่. |
| [getKumimoji()](#getKumimoji--) | กำหนดว่าตัวเลขควรละเว้นการจัดเรียงข้อความแนวตั้งที่เฉพาะเจาะจงตามภาษาตะวันออกของข้อความหรือไม่. |
| [getNormaliseHeight()](#getNormaliseHeight--) | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. |
| [getProofDisabled()](#getProofDisabled--) | กำหนดว่าข้อความไม่ควรตรวจสอบการพิสูจน์อักษรหรือไม่. |
| [getFontUnderline()](#getFontUnderline--) | คืนค่าประเภทการขีดเส้นใต้ของข้อความ. |
| [getTextCapType()](#getTextCapType--) | คืนค่าประเภทการใช้ตัวพิมพ์ใหญ่ของข้อความ. |
| [getStrikethroughType()](#getStrikethroughType--) | คืนค่าประเภทการขีดเส้นผ่านข้อความ. |
| [getSmartTagClean()](#getSmartTagClean--) | กำหนดว่าป้ายอัจฉริยะควรถูกทำความสะอาดหรือไม่. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | กำหนดว่ารูปแบบการขีดเส้นใต้มีแอตริบิวต์ LineFormat ของตนเองหรือสืบทอดจากแอตริบิวต์ LineFormat ของข้อความ. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | กำหนดว่ารูปแบบการขีดเส้นใต้มีแอตริบิวต์ FillFormat ของตนเองหรือสืบทอดจากแอตริบิวต์ FillFormat ของข้อความ. |
| [getFontHeight()](#getFontHeight--) | คืนค่าความสูงของฟอนต์ของส่วนข้อความในหน่วยจุด. |
| [getLatinFont()](#getLatinFont--) | คืนข้อมูลฟอนต์ Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | คืนข้อมูลฟอนต์เอเชียตะวันออก. |
| [getComplexScriptFont()](#getComplexScriptFont--) | คืนข้อมูลฟอนต์สคริปต์ซับซ้อน. |
| [getSymbolFont()](#getSymbolFont--) | คืนข้อมูลฟอนต์สัญลักษณ์. |
| [getEscapement()](#getEscapement--) | คืนข้อความซูเปอร์สคริปต์หรือซับสคริปต์. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | คืนขนาดฟอนต์ขั้นต่ำที่ควรเปิดใช้งานการปรับระยะห่างระหว่างตัวอักษร (kerning). |
| [getLanguageId()](#getLanguageId--) | คืนค่า Id ของภาษา. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | คืนค่า Id ของภาษาทางเลือก. |
| [getSpacing()](#getSpacing--) | คืนค่าการเพิ่มระยะห่างระหว่างอักขระในหน่วยจุด. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```


คืนค่าแอตริบิวต์ LineFormat สำหรับการร่างเส้นขอบข้อความ. อ่านอย่างเดียว [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**คืนค่า:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


คืนค่าแอตริบิวต์ FillFormat ของข้อความ. อ่านอย่างเดียว [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**คืนค่า:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


คืนค่าแอตริบิวต์ EffectFormat ของข้อความ. อ่านอย่างเดียว [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**คืนค่า:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Integer getHighlightColor()
```


คืนค่าสีที่ใช้เน้นข้อความ. อ่านอย่างเดียว java.lang.Integer.

**คืนค่า:**
java.lang.Integer
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```


คืนค่าแอตริบิวต์ LineFormat ที่ใช้ร่างเส้นขอบขีดเส้นใต้. อ่านอย่างเดียว [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**คืนค่า:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```


คืนค่าแอตริบิวต์ FillFormat ของเส้นขีดใต้. อ่านอย่างเดียว [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**คืนค่า:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```


กำหนดว่าฟอนต์เป็นตัวหนาหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```


กำหนดว่าฟอนต์เป็นตัวเอียงหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```


กำหนดว่าตัวเลขควรละเว้นการจัดเรียงข้อความแนวตั้งที่เฉพาะเจาะจงตามภาษาตะวันออกของข้อความหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```


กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```


กำหนดว่าข้อความไม่ควรตรวจสอบการพิสูจน์อักษรหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```


คืนค่าประเภทการขีดเส้นใต้ของข้อความ. อ่านอย่างเดียว [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**คืนค่า:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```


คืนค่าประเภทการใช้ตัวพิมพ์ใหญ่ของข้อความ. อ่านอย่างเดียว [TextCapType](../../com.aspose.slides/textcaptype).

**คืนค่า:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```


คืนค่าประเภทการขีดเส้นผ่านข้อความ. อ่านอย่างเดียว [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**คืนค่า:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


กำหนดว่าป้ายอัจฉริยะควรถูกทำความสะอาดหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```


กำหนดว่ารูปแบบการขีดเส้นใต้มีแอตริบิวต์ LineFormat ของตนเองหรือสืบทอดจากแอตริบิวต์ LineFormat ของข้อความ. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```


กำหนดว่ารูปแบบการขีดเส้นใต้มีแอตริบิวต์ FillFormat ของตนเองหรือสืบทอดจากแอตริบิวต์ FillFormat ของข้อความ. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```


คืนค่าความสูงของฟอนต์ของส่วนข้อความในหน่วยจุด. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


คืนข้อมูลฟอนต์ Latin. อ่านอย่างเดียว [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


คืนข้อมูลฟอนต์เอเชียตะวันออก. อ่านอย่างเดียว [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


คืนข้อมูลฟอนต์สคริปต์ซับซ้อน. อ่านอย่างเดียว [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```


คืนข้อมูลฟอนต์สัญลักษณ์. อ่านอย่างเดียว [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```


คืนข้อความซูเปอร์สคริปต์หรือซับสคริปต์. ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซูเปอร์สคริปต์). อ่านอย่างเดียว float.

**คืนค่า:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```


คืนขนาดฟอนต์ขั้นต่ำที่ควรเปิดใช้งานการปรับระยะห่างระหว่างตัวอักษร (kerning). อ่านอย่างเดียว float.

**คืนค่า:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```


คืนค่า Id ของภาษา. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```


คืนค่า Id ของภาษาทางเลือก. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```


คืนค่าการเพิ่มระยะห่างระหว่างอักขระในหน่วยจุด. อ่านอย่างเดียว float.

**คืนค่า:**
float