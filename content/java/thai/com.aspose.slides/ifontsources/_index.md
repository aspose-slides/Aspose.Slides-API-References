---
title: IFontSources
second_title: Aspose.Slides for Java API Reference
description: ให้แหล่งไฟล์และหน่วยความจำสำหรับฟอนต์ภายนอก.
type: docs
url: /th/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

ให้แหล่งไฟล์และหน่วยความจำสำหรับฟอนต์ภายนอก.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | โฟลเดอร์ที่มีไฟล์ฟอนต์. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | โฟลเดอร์ที่มีไฟล์ฟอนต์. |
| [getMemoryFonts()](#getMemoryFonts--) | คอลเลกชันของฟอนต์ที่แสดงเป็นอาร์เรย์ของไบต์. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | คอลเลกชันของฟอนต์ที่แสดงเป็นอาร์เรย์ของไบต์. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```


โฟลเดอร์ที่มีไฟล์ฟอนต์. ไฟล์ฟอนต์ทั้งหมดที่อยู่ในโฟลเดอร์เหล่านี้จะถูกรวมอยู่ในคอลเลกชัน โฟลเดอร์เหล่านี้จะถูกค้นหาแบบเรียกซ้ำ.

**คืนค่า:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```


โฟลเดอร์ที่มีไฟล์ฟอนต์. ไฟล์ฟอนต์ทั้งหมดที่อยู่ในโฟลเดอร์เหล่านี้จะถูกรวมอยู่ในคอลเลกชัน โฟลเดอร์เหล่านี้จะถูกค้นหาแบบเรียกซ้ำ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```


คอลเลกชันของฟอนต์ที่แสดงเป็นอาร์เรย์ของไบต์.

**คืนค่า:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```


คอลเลกชันของฟอนต์ที่แสดงเป็นอาร์เรย์ของไบต์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte[][] |  |