---
title: ICommentAuthorCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: เป็นตัวแทนของคอลเลกชันของผู้เขียนความคิดเห็น.
type: docs
url: /th/com.aspose.slides/icommentauthorcollection/
---
**ทั้งหมดของอินเทอร์เฟซที่ใช้งาน:**  
com.aspose.slides.IGenericCollection  
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

เป็นตัวแทนของคอลเลกชันของผู้เขียนความคิดเห็น  
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงองค์ประกอบที่ตำแหน่งดัชนีที่ระบุ. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | เพิ่มผู้เขียนใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [toArray()](#toArray--) | สร้างและคืนค่าอาเรย์ที่มีผู้เขียนทั้งหมด. |
| [findByName(String name)](#findByName-java.lang.String-) | ค้นหาผู้เขียนในคอลเลกชันโดยชื่อ. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | ค้นหาผู้เขียนในคอลเลกชันโดยชื่อและอักษรย่อ. |
| [removeAt(int index)](#removeAt-int-) | ลบผู้เขียนที่ตำแหน่งดัชนีที่ระบุของคอลเลกชัน. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | ลบการปรากฏครั้งแรกของผู้เขียนที่ระบุในคอลเลกชัน. |
| [clear()](#clear--) | ลบผู้เขียนทั้งหมดจากคอลเลกชัน. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```

ดึงองค์ประกอบที่ตำแหน่งดัชนีที่ระบุ. อ่านอย่างเดียว [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```

เพิ่มผู้เขียนใหม่ที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| name | java.lang.String | ชื่อของผู้เขียนใหม่. |
| initials | java.lang.String | อักษรย่อของผู้เขียนใหม่. |

**คืนค่า:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - วัตถุใหม่ [ICommentAuthor](../../com.aspose.slides/icommentauthor).
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```

สร้างและคืนค่าอาเรย์ที่มีผู้เขียนทั้งหมด.

**คืนค่า:**
com.aspose.slides.ICommentAuthor[] - อาเรย์ของ [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```

ค้นหาผู้เขียนในคอลเลกชันโดยชื่อ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| name | java.lang.String | ชื่อของผู้เขียนที่ต้องการค้นหา. |

**คืนค่า:**
com.aspose.slides.ICommentAuthor[] - ผู้เขียนหรือ null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

ค้นหาผู้เขียนในคอลเลกชันโดยชื่อและอักษรย่อ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| name | java.lang.String | ชื่อของผู้เขียนที่ต้องการค้นหา. |
| initials | java.lang.String | อักษรย่อของผู้เขียนที่ต้องการค้นหา. |

**คืนค่า:**
com.aspose.slides.ICommentAuthor[] - ผู้เขียนหรือ null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบผู้เขียนที่ตำแหน่งดัชนีที่ระบุของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นจากศูนย์ขององค์ประกอบที่ต้องการลบ. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```

ลบการปรากฏครั้งแรกของผู้เขียนที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | ผู้เขียนที่จะลบออกจากคอลเลกชัน. |

### clear() {#clear--}
```
public abstract void clear()
```

ลบผู้เขียนทั้งหมดจากคอลเลกชัน.