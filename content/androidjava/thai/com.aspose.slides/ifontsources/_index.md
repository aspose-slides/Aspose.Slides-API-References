---
title: IFontSources
second_title: Aspose.Slides for Android via Java API Reference
description: Provides file and memory sources for external fonts.
type: docs
url: /th/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

ให้แหล่งข้อมูลไฟล์และหน่วยความจำสำหรับฟอนต์ภายนอก
## เมธอด

| Method | Description |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | โฟลเดอร์ที่มีไฟล์ฟอนต์ |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | โฟลเดอร์ที่มีไฟล์ฟอนต์ |
| [getMemoryFonts()](#getMemoryFonts--) | คอลเลกชันของฟอนต์ที่แสดงเป็นอาร์เรย์ของไบต์ |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | คอลเลกชันของฟอนต์ที่แสดงเป็นอาร์เรย์ของไบต์ |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

โฟลเดอร์ที่มีไฟล์ฟอนต์ ทั้งหมดของไฟล์ฟอนต์ที่อยู่ในโฟลเดอร์เหล่านี้จะถูกรวมอยู่ในคอลเลกชัน โฟลเดอร์ที่ถูกค้นหาแบบเรียงลำดับซ้ำ

**คืนค่า:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

โฟลเดอร์ที่มีไฟล์ฟอนต์ ทั้งหมดของไฟล์ฟอนต์ที่อยู่ในโฟลเดอร์เหล่านี้จะถูกรวมอยู่ในคอลเลกชัน โฟลเดอร์ที่ถูกค้นหาแบบเรียงลำดับซ้ำ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

คอลเลกชันของฟอนต์ที่แสดงเป็นอาร์เรย์ของไบต์

**คืนค่า:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

คอลเลกชันของฟอนต์ที่แสดงเป็นอาร์เรย์ของไบต์

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[][] |  |