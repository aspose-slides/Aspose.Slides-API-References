---
title: ISlideText
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงข้อความที่ดึงมาจากสไลด์
type: docs
url: /th/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

แสดงข้อความที่ดึงมาจากสไลด์
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getText()](#getText--) | ข้อความบนรูปร่างของสไลด์ |
| [getMasterText()](#getMasterText--) | ข้อความบนรูปร่างของหน้าแม่สำหรับสไลด์นี้ |
| [getLayoutText()](#getLayoutText--) | ข้อความบนรูปร่างของหน้าเลย์เอาท์สำหรับสไลด์นี้ |
| [getNotesText()](#getNotesText--) | ข้อความบนรูปร่างของหน้าบันทึกย่อสำหรับสไลด์นี้ |
| [getCommentsText()](#getCommentsText--) | ข้อความของความคิดเห็นสไลด์ |
### getText() {#getText--}
```
public abstract String getText()
```

ข้อความบนรูปร่างของสไลด์

**คืนค่า:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```

ข้อความบนรูปร่างของหน้าแม่สำหรับสไลด์นี้

**คืนค่า:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```

ข้อความบนรูปร่างของหน้าเลย์เอาท์สำหรับสไลด์นี้

**คืนค่า:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```

ข้อความบนรูปร่างของหน้าบันทึกย่อสำหรับสไลด์นี้

**คืนค่า:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```

ข้อความของความคิดเห็นสไลด์

--------------------

ฟิลด์นี้จะว่างเมื่อข้อความถูกสกัดโดยใช้โหมด Arranged

**คืนค่า:**
java.lang.String