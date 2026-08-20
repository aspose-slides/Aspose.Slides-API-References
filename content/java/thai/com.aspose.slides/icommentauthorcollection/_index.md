---
title: ICommentAuthorCollection
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: เป็นคอลเลกชันของผู้เขียนความคิดเห็น.
type: docs
url: /th/com.aspose.slides/icommentauthorcollection/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

เป็นคอลเลกชันของผู้เขียนความคิดเห็น.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | เพิ่มผู้เขียนใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [toArray()](#toArray--) | สร้างและคืนค่าอาร์เรย์ที่มีผู้เขียนทั้งหมด. |
| [findByName(String name)](#findByName-java.lang.String-) | ค้นหาผู้เขียนในคอลเลกชันตามชื่อ. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | ค้นหาผู้เขียนในคอลเลกชันตามชื่อและอักษรย่อ. |
| [removeAt(int index)](#removeAt-int-) | ลบผู้เขียนที่ตำแหน่งที่ระบุของคอลเลกชัน. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | ลบการปรากฏครั้งแรกของผู้เขียนที่ระบุในคอลเลกชัน. |
| [clear()](#clear--) | ลบผู้เขียนทั้งหมดจากคอลเลกชัน. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```


ดึงองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```


เพิ่มผู้เขียนใหม่ที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของผู้เขียนใหม่. |
| initials | java.lang.String | อักษรย่อของผู้เขียนใหม่. |

**ผลลัพธ์:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - วัตถุ [ICommentAuthor](../../com.aspose.slides/icommentauthor) ใหม่.
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```


สร้างและคืนค่าอาร์เรย์ที่มีผู้เขียนทั้งหมด.

**ผลลัพธ์:**
com.aspose.slides.ICommentAuthor[] - อาร์เรย์ของ [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```


ค้นหาผู้เขียนในคอลเลกชันตามชื่อ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของผู้เขียนที่ต้องการค้นหา. |

**ผลลัพธ์:**
com.aspose.slides.ICommentAuthor[] - ผู้เขียนหรือ null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


ค้นหาผู้เขียนในคอลเลกชันตามชื่อและอักษรย่อ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของผู้เขียนที่ต้องการค้นหา. |
| initials | java.lang.String | อักษรย่อของผู้เขียนที่ต้องการค้นหา. |

**ผลลัพธ์:**
com.aspose.slides.ICommentAuthor[] - ผู้เขียนหรือ null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


ลบผู้เขียนที่ตำแหน่งที่ระบุของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่เริ่มจากศูนย์ขององค์ประกอบที่ต้องการลบ. |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```


ลบการปรากฏครั้งแรกของผู้เขียนที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | ผู้เขียนที่ต้องการลบออกจากคอลเลกชัน. |
### clear() {#clear--}
```
public abstract void clear()
```


ลบผู้เขียนทั้งหมดออกจากคอลเลกชัน.