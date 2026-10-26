---
title: FontSubstRule
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงข้อมูลการแทนที่ฟอนต์
type: docs
url: /th/com.aspose.slides/fontsubstrule/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ Implement ทั้งหมด:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

แสดงข้อมูลการแทนที่ฟอนต์
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | สร้างอินสแตนซ์ใหม่ |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | สร้างอินสแตนซ์ใหม่ |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | ฟอนต์ที่ต้องแทนที่ |
| [getDestFont()](#getDestFont--) | ฟอนต์ที่ใช้สำหรับการแทนที่ |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | กฎที่ใช้สำหรับการแทนที่ |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```

สร้างอินสแตนซ์ใหม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | ฟอนต์ต้นฉบับ |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | ฟอนต์ปลายทาง |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```

สร้างอินสแตนซ์ใหม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | ฟอนต์ต้นฉบับ |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | ฟอนต์ปลายทาง |
| fontSubstRule | int | กฎการแทนที่ฟอนต์ |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```

ฟอนต์ที่ต้องแทนที่. อ่านอย่างเดียว [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```

ฟอนต์ที่ใช้สำหรับการแทนที่. อ่านอย่างเดียว [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```

กฎที่ใช้สำหรับการแทนที่. อ่านอย่างเดียว [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**คืนค่า:**
int