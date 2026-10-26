---
title: NotesCommentsLayoutingOptions
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ให้ตัวเลือกที่ควบคุมรูปลักษณ์การจัดวางของบันทึกย่อและความคิดเห็นในเอกสารที่ส่งออก
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

ให้ตัวเลือกที่ควบคุมลักษณะการจัดวางของบันทึกย่อและความคิดเห็นในเอกสารที่ส่งออก

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
| [getCommentsAreaColor()](#getCommentsAreaColor--) | รับหรือกำหนดสีของพื้นที่ความคิดเห็น (ใช้เฉพาะเมื่อตัวความคิดเห็นแสดงที่ด้านขวา). |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | รับหรือกำหนดสีของพื้นที่ความคิดเห็น (ใช้เฉพาะเมื่อตัวความคิดเห็นแสดงที่ด้านขวา). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | รับหรือกำหนดความกว้างของพื้นที่แสดงผลความคิดเห็นเป็นพิกเซล (ใช้เฉพาะเมื่อตัวความคิดเห็นแสดงที่ด้านขวา). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | รับหรือกำหนดความกว้างของพื้นที่แสดงผลความคิดเห็นเป็นพิกเซล (ใช้เฉพาะเมื่อตัวความคิดเห็นแสดงที่ด้านขวา). |

### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

คอนสตรัคเตอร์เริ่มต้น.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

รับหรือกำหนดการมองเห็นของความคิดเห็นที่ไม่มีผู้เขียน. หากเป็น true แล้วความคิดเห็นจะถูกแสดง (ใช้เฉพาะเมื่อตัวความคิดเห็นแสดง)

--------------------

ค่าเริ่มต้นคือ **false**.

**คืนค่า:**  
boolean

### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

รับหรือกำหนดการมองเห็นของความคิดเห็นที่ไม่มีผู้เขียน. หากเป็น true แล้วความคิดเห็นจะถูกแสดง (ใช้เฉพาะเมื่อตัวความคิดเห็นแสดง)

--------------------

ค่าเริ่มต้นคือ **false**.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

รับหรือกำหนดตำแหน่งของบันทึกย่อบนหน้า.

--------------------

ค่าเริ่มต้นคือ **NotesPositions.None**.

**คืนค่า:**  
int

### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

รับหรือกำหนดตำแหน่งของบันทึกย่อบนหน้า.

--------------------

ค่าเริ่มต้นคือ **NotesPositions.None**.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

รับหรือกำหนดตำแหน่งของความคิดเห็นบนหน้า.

--------------------

ค่าเริ่มต้นคือ **CommentsPositions.None**.

**คืนค่า:**  
int

### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

รับหรือกำหนดตำแหน่งของความคิดเห็นบนหน้า.

--------------------

ค่าเริ่มต้นคือ **CommentsPositions.None**.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Color getCommentsAreaColor()
```

รับหรือกำหนดสีของพื้นที่ความคิดเห็น (ใช้เฉพาะเมื่อตัวความคิดเห็นแสดงที่ด้านขวา).

--------------------

ค่าเริ่มต้นคือ **Color.SkyBlue**.

**คืนค่า:**  
java.awt.Color

### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public final void setCommentsAreaColor(Color value)
```

รับหรือกำหนดสีของพื้นที่ความคิดเห็น (ใช้เฉพาะเมื่อตัวความคิดเห็นแสดงที่ด้านขวา).

--------------------

ค่าเริ่มต้นคือ **Color.SkyBlue**.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.awt.Color |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

รับหรือกำหนดความกว้างของพื้นที่แสดงผลความคิดเห็นเป็นพิกเซล (ใช้เฉพาะเมื่อตัวความคิดเห็นแสดงที่ด้านขวา).

--------------------

ค่าต่ำสุดและค่าเริ่มต้นคือ **150**.

**คืนค่า:**  
int

### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

รับหรือกำหนดความกว้างของพื้นที่แสดงผลความคิดเห็นเป็นพิกเซล (ใช้เฉพาะเมื่อตัวความคิดเห็นแสดงที่ด้านขวา).

--------------------

ค่าต่ำสุดและค่าเริ่มต้นคือ **150**.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |