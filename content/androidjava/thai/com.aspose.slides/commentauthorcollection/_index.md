---
title: CommentAuthorCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นคอลเลกชันของผู้เขียนความคิดเห็น.
type: docs
url: /th/com.aspose.slides/commentauthorcollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

เป็นคอลเลกชันของผู้เขียนความคิดเห็น.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | รับจำนวนขององค์ประกอบที่อยู่จริงในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | เพิ่มผู้เขียนใหม่ที่ท้ายของคอลเลกชัน |
| [toArray()](#toArray--) | สร้างและคืนอาร์เรย์ที่มีผู้เขียนทั้งหมด |
| [findByName(String name)](#findByName-java.lang.String-) | ค้นหาผู้เขียนในคอลเลกชันตามชื่อ |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | ค้นหาผู้เขียนในคอลเลกชันตามชื่อและอักษรย่อ |
| [removeAt(int index)](#removeAt-int-) | ลบผู้เขียนที่ตำแหน่งที่ระบุในคอลเลกชัน |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | ลบการปรากฏครั้งแรกของผู้เขียนที่ระบุในคอลเลกชัน |
| [clear()](#clear--) | ลบผู้เขียนทั้งหมดออกจากคอลเลกชัน |
| [iterator()](#iterator--) | คืน enumerator ที่วนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืน java iterator สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกรายการทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันนั้น synchronized (thread-safe) หรือไม่ |
| [getSyncRoot()](#getSyncRoot--) | คืน synchronization root |

### size() {#size--}
```
public final int size()
```

รับจำนวนขององค์ประกอบที่อยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)

### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```

เพิ่มผู้เขียนใหม่ที่ท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของผู้เขียนใหม่. |
| initials | java.lang.String | อักษรย่อของผู้เขียนใหม่. |

**คืนค่า:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - ออบเจ็กต์ [ICommentAuthor](../../com.aspose.slides/icommentauthor) ใหม่.

### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

สร้างและคืนอาร์เรย์ที่มีผู้เขียนทั้งหมด.

**คืนค่า:**
com.aspose.slides.ICommentAuthor[] - อาร์เรย์ของ [ICommentAuthor](../../com.aspose.slides/icommentauthor)

### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

ค้นหาผู้เขียนในคอลเลกชันตามชื่อ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของผู้เขียนที่ต้องการค้นหา. |

**คืนค่า:**
com.aspose.slides.ICommentAuthor[] - ผู้เขียนหรือ null.

### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

ค้นหาผู้เขียนในคอลเลกชันตามชื่อและอักษรย่อ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของผู้เขียนที่ต้องการค้นหา. |
| initials | java.lang.String | อักษรย่อของผู้เขียนที่ต้องการค้นหา. |

**คืนค่า:**
com.aspose.slides.ICommentAuthor[] - ผู้เขียนหรือ null.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบผู้เขียนที่ตำแหน่งที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นจากศูนย์ขององค์ประกอบที่ต้องการลบ. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

ลบการปรากฏครั้งแรกของผู้เขียนที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | ผู้เขียนที่ต้องการลบจากคอลเลกชัน. |

### clear() {#clear--}
```
public final void clear()
```

ลบผู้เขียนทั้งหมดออกจากคอลเลกชัน.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

คืน enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - IGenericEnumerator ที่สามารถใช้เพื่อวนซ้ำผ่านคอลเลกชัน

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

คืน java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกรายการทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย. |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันนั้น synchronized (thread-safe) หรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืน synchronization root. อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object