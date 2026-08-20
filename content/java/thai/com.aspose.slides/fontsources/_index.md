---
title: FontSources
second_title: Aspose.Slides สำหรับ Java API Reference
description: ให้แหล่งไฟล์และหน่วยความจำสำหรับแบบอักษรภายนอก
type: docs
url: /th/com.aspose.slides/fontsources/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)  
```
public class FontSources implements IFontSources
```

ให้แหล่งไฟล์และหน่วยความจำสำหรับแบบอักษรภายนอก

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [FontSources()](#FontSources--) | สร้างตัวเลือกแบบอักษรเริ่มต้นใหม่ |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | โฟลเดอร์ที่มีไฟล์แบบอักษร |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | โฟลเดอร์ที่มีไฟล์แบบอักษร |
| [getMemoryFonts()](#getMemoryFonts--) | คอลเลกชันของแบบอักษรที่เป็นอาร์เรย์ของไบต์ |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | คอลเลกชันของแบบอักษรที่เป็นอาร์เรย์ของไบต์ |

### FontSources() {#FontSources--}
```
public FontSources()
```

สร้างตัวเลือกแบบอักษรเริ่มต้นใหม่

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```

โฟลเดอร์ที่มีไฟล์แบบอักษร ไฟล์แบบอักษรทั้งหมดที่อยู่ในโฟลเดอร์เหล่านี้จะถูกรวมอยู่ในคอลเลกชัน โฟลเดอร์ที่ถูกค้นหาแบบเรียกซ้ำ

**ส่งคืน:**  
java.lang.String[]

### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```

โฟลเดอร์ที่มีไฟล์แบบอักษร ไฟล์แบบอักษรทั้งหมดที่อยู่ในโฟลเดอร์เหล่านี้จะถูกรวมอยู่ในคอลเลกชัน โฟลเดอร์ที่ถูกค้นหาแบบเรียกซ้ำ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```

คอลเลกชันของแบบอักษรที่เป็นอาร์เรย์ของไบต์

**ส่งคืน:**  
byte[][]

### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```

คอลเลกชันของแบบอักษรที่เป็นอาร์เรย์ของไบต์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte[][] |  |