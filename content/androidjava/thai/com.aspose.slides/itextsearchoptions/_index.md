---
title: ITextSearchOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents options that can be used to search for text in a Presentation Slide or TextFrame.
type: docs
url: /th/com.aspose.slides/itextsearchoptions/
---```
public interface ITextSearchOptions
```

แสดงตัวเลือกที่สามารถใช้เพื่อค้นหาข้อความใน Presentation, Slide หรือ TextFrame.
## เมธอด

| Method | Description |
| --- | --- |
| [getCaseSensitive()](#getCaseSensitive--) | ตั้งค่าเป็น true เพื่อใช้การค้นหาที่แยกแยะตัวพิมพ์ใหญ่/เล็ก, false - ในกรณีอื่น. |
| [setCaseSensitive(boolean value)](#setCaseSensitive-boolean-) | ตั้งค่าเป็น true เพื่อใช้การค้นหาที่แยกแยะตัวพิมพ์ใหญ่/เล็ก, false - ในกรณีอื่น. |
| [getWholeWordsOnly()](#getWholeWordsOnly--) | ตั้งค่าเป็น true เพื่อจับคู่เฉพาะคำเต็ม, false - ในกรณีอื่น. |
| [setWholeWordsOnly(boolean value)](#setWholeWordsOnly-boolean-) | ตั้งค่าเป็น true เพื่อจับคู่เฉพาะคำเต็ม, false - ในกรณีอื่น. |
| [getIncludeNotes()](#getIncludeNotes--) | ตั้งค่าเป็น true เพื่อรวมข้อความที่อยู่ในบันทึกสไลด์เมื่อต้องทำการค้นหาข้อความ, การแทนที่ หรือการไฮไลท์. |
| [setIncludeNotes(boolean value)](#setIncludeNotes-boolean-) | ตั้งค่าเป็น true เพื่อรวมข้อความที่อยู่ในบันทึกสไลด์เมื่อต้องทำการค้นหาข้อความ, การแทนที่ หรือการไฮไลท์. |
### getCaseSensitive() {#getCaseSensitive--}
```
public abstract boolean getCaseSensitive()
```


ตั้งค่าเป็น true เพื่อใช้การค้นหาที่แยกแยะตัวพิมพ์ใหญ่/เล็ก, false - ในกรณีอื่น. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setCaseSensitive(boolean value) {#setCaseSensitive-boolean-}
```
public abstract void setCaseSensitive(boolean value)
```


ตั้งค่าเป็น true เพื่อใช้การค้นหาที่แยกแยะตัวพิมพ์ใหญ่/เล็ก, false - ในกรณีอื่น. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWholeWordsOnly() {#getWholeWordsOnly--}
```
public abstract boolean getWholeWordsOnly()
```


ตั้งค่าเป็น true เพื่อจับคู่เฉพาะคำเต็ม, false - ในกรณีอื่น. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setWholeWordsOnly(boolean value) {#setWholeWordsOnly-boolean-}
```
public abstract void setWholeWordsOnly(boolean value)
```


ตั้งค่าเป็น true เพื่อจับคู่เฉพาะคำเต็ม, false - ในกรณีอื่น. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getIncludeNotes() {#getIncludeNotes--}
```
public abstract boolean getIncludeNotes()
```


ตั้งค่าเป็น true เพื่อรวมข้อความที่อยู่ในบันทึกสไลด์เมื่อต้องทำการค้นหาข้อความ, การแทนที่ หรือการไฮไลท์. ค่าปริยายคือ false.

**ผลลัพธ์:**
boolean
### setIncludeNotes(boolean value) {#setIncludeNotes-boolean-}
```
public abstract void setIncludeNotes(boolean value)
```


ตั้งค่าเป็น true เพื่อรวมข้อความที่อยู่ในบันทึกสไลด์เมื่อต้องทำการค้นหาข้อความ, การแทนที่ หรือการไฮไลท์. ค่าปริยายคือ false.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |