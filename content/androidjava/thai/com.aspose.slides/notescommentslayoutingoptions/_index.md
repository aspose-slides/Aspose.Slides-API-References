---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ให้ตัวเลือกที่ควบคุมรูปลักษณ์ของการจัดวางบันทึกย่อและความคิดเห็นในเอกสารที่ส่งออก
type: docs
url: /th/com.aspose.slides/notescommentslayoutingoptions/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

ให้ตัวเลือกที่ควบคุมรูปลักษณ์ของการจัดวางบันทึกย่อและความคิดเห็นในเอกสารที่ส่งออก
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | คอนสตรัคเตอร์เริ่มต้น. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | รับหรือกำหนดการมองเห็นของความคิดเห็นที่ไม่มีผู้เขียน. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | รับหรือกำหนดการมองเห็นของความคิดเห็นที่ไม่มีผู้เขียน. |
| [getNotesPosition()](#getNotesPosition--) | รับหรือกำหนดตำแหน่งของบันทึกย่อบนหน้า. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | รับหรือกำหนดตำแหน่งของบันทึกย่อบนหน้า. |
| [getCommentsPosition()](#getCommentsPosition--) | รับหรือกำหนดตำแหน่งของความคิดเห็นบนหน้า. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | รับหรือกำหนดตำแหน่งของความคิดเห็นบนหน้า. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | รับหรือกำหนดสีของพื้นที่ความคิดเห็น (ใช้เฉพาะเมื่อความคิดเห็นแสดงทางด้านขวา). |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | รับหรือกำหนดสีของพื้นที่ความคิดเห็น (ใช้เฉพาะเมื่อความคิดเห็นแสดงทางด้านขวา). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | รับหรือกำหนดความกว้างของพื้นที่แสดงความคิดเห็นเป็นพิกเซล (ใช้เฉพาะเมื่อความคิดเห็นแสดงทางด้านขวา). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | รับหรือกำหนดความกว้างของพื้นที่แสดงความคิดเห็นเป็นพิกเซล (ใช้เฉพาะเมื่อความคิดเห็นแสดงทางด้านขวา). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```


คอนสตรัคเตอร์เริ่มต้น.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```


รับหรือกำหนดการมองเห็นของความคิดเห็นที่ไม่มีผู้เขียน หากเป็นจริงแล้วความคิดเห็นจะถูกแสดง (ใช้เฉพาะเมื่อความคิดเห็นถูกแสดง).

--------------------

ค่าตั้งต้นคือ **false**.

**ค่าที่ส่งกลับ:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```


รับหรือกำหนดการมองเห็นของความคิดเห็นที่ไม่มีผู้เขียน หากเป็นจริงแล้วความคิดเห็นจะถูกแสดง (ใช้เฉพาะเมื่อความคิดเห็นถูกแสดง).

--------------------

ค่าตั้งต้นคือ **false**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```


รับหรือกำหนดตำแหน่งของบันทึกย่อบนหน้า.

--------------------

ค่าเริ่มต้นคือ **NotesPositions.None**.

**ค่าที่ส่งกลับ:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```


รับหรือกำหนดตำแหน่งของบันทึกย่อบนหน้า.

--------------------

ค่าเริ่มต้นคือ **NotesPositions.None**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```


รับหรือกำหนดตำแหน่งของความคิดเห็นบนหน้า.

--------------------

ค่าเริ่มต้นคือ **CommentsPositions.None**.

**ค่าที่ส่งกลับ:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```


รับหรือกำหนดตำแหน่งของความคิดเห็นบนหน้า.

--------------------

ค่าเริ่มต้นคือ **CommentsPositions.None**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```


รับหรือกำหนดสีของพื้นที่ความคิดเห็น (ใช้เฉพาะเมื่อความคิดเห็นแสดงทางด้านขวา).

--------------------

ค่าเริ่มต้นคือ **SkyBlue**.

**ค่าที่ส่งกลับ:**
java.lang.Integer
### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```


รับหรือกำหนดสีของพื้นที่ความคิดเห็น (ใช้เฉพาะเมื่อความคิดเห็นแสดงทางด้านขวา).

--------------------

ค่าเริ่มต้นคือ **SkyBlue**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```


รับหรือกำหนดความกว้างของพื้นที่แสดงความคิดเห็นเป็นพิกเซล (ใช้เฉพาะเมื่อความคิดเห็นแสดงทางด้านขวา).

--------------------

ค่าต่ำสุดและค่าเริ่มต้นคือ **150**.

**ค่าที่ส่งกลับ:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```


รับหรือกำหนดความกว้างของพื้นที่แสดงความคิดเห็นเป็นพิกเซล (ใช้เฉพาะเมื่อความคิดเห็นแสดงทางด้านขวา).

--------------------

ค่าต่ำสุดและค่าเริ่มต้นคือ **150**.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |