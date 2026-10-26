---
title: ICommentAuthor
second_title: Aspose.Slides for Java API Reference
description: Represents an author of comments.
type: docs
url: /th/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

แสดงถึงผู้เขียนความคิดเห็น.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getName()](#getName--) | คืนค่าหรือกำหนดชื่อผู้เขียน |
| [setName(String value)](#setName-java.lang.String-) | คืนค่าหรือกำหนดชื่อผู้เขียน |
| [getInitials()](#getInitials--) | คืนค่าหรือกำหนดอักษรย่อของผู้เขียน |
| [setInitials(String value)](#setInitials-java.lang.String-) | คืนค่าหรือกำหนดอักษรย่อของผู้เขียน |
| [getComments()](#getComments--) | คืนค่าคอลเลกชันของความคิดเห็นที่สร้างโดยผู้เขียนนี้ |
| [remove()](#remove--) | ลบผู้เขียนออกจากคอลเลกชันหลัก |
### getName() {#getName--}
```
public abstract String getName()
```


คืนค่าหรือกำหนดชื่อผู้เขียน อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


คืนค่าหรือกำหนดชื่อผู้เขียน อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getInitials() {#getInitials--}
```
public abstract String getInitials()
```


คืนค่าหรือกำหนดอักษรย่อของผู้เขียน อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```


คืนค่าหรือกำหนดอักษรย่อของผู้เขียน อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```


คืนค่าคอลเลกชันของความคิดเห็นที่สร้างโดยผู้เขียนนี้ อ่านอย่างเดียว [ICommentCollection](../../com.aspose.slides/icommentcollection).

**คืนค่า:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```


ลบผู้เขียนออกจากคอลเลกชันหลัก.