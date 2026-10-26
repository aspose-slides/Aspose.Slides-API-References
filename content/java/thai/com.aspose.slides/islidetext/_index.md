---
title: ISlideText
second_title: Aspose.Slides for Java API Reference
description: Represents the text extracted from the slide
type: docs
url: /th/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

แสดงถึงข้อความที่สกัดจากสไลด์
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [getText()](#getText--) | ข้อความบนรูปร่างของสไลด์ |
| [getMasterText()](#getMasterText--) | ข้อความบนรูปร่างของหน้า master สำหรับสไลด์นี้ |
| [getLayoutText()](#getLayoutText--) | ข้อความบนรูปร่างของหน้า layout สำหรับสไลด์นี้ |
| [getNotesText()](#getNotesText--) | ข้อความบนรูปร่างของหน้า notes สำหรับสไลด์นี้ |
| [getCommentsText()](#getCommentsText--) | ข้อความของคอมเมนต์สไลด์ |
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


ข้อความบนรูปร่างของหน้า master สำหรับสไลด์นี้

**คืนค่า:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```


ข้อความบนรูปร่างของหน้า layout สำหรับสไลด์นี้

**คืนค่า:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```


ข้อความบนรูปร่างของหน้า notes สำหรับสไลด์นี้

**คืนค่า:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```


ข้อความของคอมเมนต์สไลด์

--------------------

ฟิลด์นี้จะว่างเปล่าเมื่อข้อความถูกสกัดโดยใช้โหมด Arranged.

**คืนค่า:**
java.lang.String