---
title: FontSubstRule
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงข้อมูลการทดแทนแบบอักษร
type: docs
url: /th/com.aspose.slides/fontsubstrule/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

แสดงข้อมูลการทดแทนแบบอักษร

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | สร้างอินสแตนซ์ใหม่. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | สร้างอินสแตนซ์ใหม่. |
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | แบบอักษรที่จะทดแทน. |
| [getDestFont()](#getDestFont--) | แบบอักษรที่จะใช้สำหรับการทดแทน. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | กฎที่จะใช้สำหรับการทดแทน. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


สร้างอินสแตนซ์ใหม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | แบบอักษรต้นทาง. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | แบบอักษรปลายทาง. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


สร้างอินสแตนซ์ใหม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | แบบอักษรต้นทาง. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | แบบอักษรปลายทาง. |
| fontSubstRule | int | กฎการทดแทนแบบอักษร. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


แบบอักษรที่จะทดแทน. อ่านอย่างเดียว [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


แบบอักษรที่จะใช้สำหรับการทดแทน. อ่านอย่างเดียว [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


กฎที่จะใช้สำหรับการทดแทน. อ่านอย่างเดียว [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**คืนค่า:**
int