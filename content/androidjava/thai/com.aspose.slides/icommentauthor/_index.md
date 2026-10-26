---
title: ICommentAuthor
second_title: Aspose.Slides for Android ผ่าน Java API Reference
description: แสดงผู้เขียนของความคิดเห็น.
type: docs
url: /th/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

แสดงผู้เขียนของความคิดเห็น.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getName()](#getName--) | คืนค่า หรือ ตั้งค่าชื่อของผู้เขียน. |
| [setName(String value)](#setName-java.lang.String-) | คืนค่า หรือ ตั้งค่าชื่อของผู้เขียน. |
| [getInitials()](#getInitials--) | คืนค่า หรือ ตั้งค่าอักษรย่อของผู้เขียน. |
| [setInitials(String value)](#setInitials-java.lang.String-) | คืนค่า หรือ ตั้งค่าอักษรย่อของผู้เขียน. |
| [getComments()](#getComments--) | คืนค่าคอลเลกชันของความคิดเห็นที่ผู้เขียนนี้สร้าง. |
| [remove()](#remove--) | ลบผู้เขียนออกจากคอลเลกชันแม่. |
### getName() {#getName--}
```
public abstract String getName()
```


คืนค่า หรือ ตั้งค่าชื่อของผู้เขียน. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


คืนค่า หรือ ตั้งค่าชื่อของผู้เขียน. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getInitials() {#getInitials--}
```
public abstract String getInitials()
```


คืนค่า หรือ ตั้งค่าอักษรย่อของผู้เขียน. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```


คืนค่า หรือ ตั้งค่าอักษรย่อของผู้เขียน. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```


คืนค่าคอลเลกชันของความคิดเห็นที่ผู้เขียนนี้สร้าง. อ่านอย่างเดียว [ICommentCollection](../../com.aspose.slides/icommentcollection).

**คืนค่า:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```


ลบผู้เขียนออกจากคอลเลกชันหลัก.