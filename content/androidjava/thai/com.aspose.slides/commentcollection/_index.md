---
title: CommentCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นการแทนคอลเลกชันของคอมเมนต์ของผู้เขียนหนึ่งคน.
type: docs
url: /th/com.aspose.slides/commentcollection/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่นำมาใช้งานทั้งหมด:**  
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)  
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

แทนที่คอลเลกชันของคอมเมนต์ของผู้เขียนหนึ่งคน.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | รับจำนวนของสมาชิกที่อยู่จริงในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | เพิ่มคอมเมนต์ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | เพิ่มคอมเมนต์สมัยใหม่ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | แทรกคอมเมนต์ใหม่ลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | แทรกคอมเมนต์สมัยใหม่ใหม่ลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [toArray()](#toArray--) | สร้างและคืนค่าอาร์เรย์ที่มีคอมเมนต์ทั้งหมด |
| [toArray(int startIndex, int count)](#toArray-int-int-) | สร้างและคืนค่าอาร์เรย์ที่มีคอมเมนต์ทั้งหมดจากช่วงที่ระบุ |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | ลบการเกิดครั้งแรกของคอมเมนต์ที่ระบุในคอลเลกชัน |
| [clear()](#clear--) | ลบคอมเมนต์ทั้งหมดออกจากคอลเลกชัน |
| [iterator()](#iterator--) | คืนค่า enumerator ที่ทำการวนลูปผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | ค้นหาคอมเมนต์ในคอลเลกชันโดยใช้ตำแหน่ง |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันนี้เป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | คืนค่า synchronization root |

### size() {#size--}
```
public final int size()
```

รับจำนวนของสมาชิกที่อยู่จริงในคอลเลกชัน อ่านอย่างเดียว  int .

**คืนค่า:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [Comment](../../com.aspose.slides/comment).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IComment](../../com.aspose.slides/icomment)

### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

เพิ่มคอมเมนต์ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความธรรมดาของคอมเมนต์ใหม่ |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ในงานนำเสนอที่ต้องการเพิ่มคอมเมนต์ใหม่ |
| position | android.graphics.PointF | ตำแหน่งบนสไลด์ที่ต้องการเพิ่มคอมเมนต์ใหม่ |
| creationTime | java.util.Date | เวลาที่สร้างคอมเมนต์ |

**คืนค่า:**
[IComment](../../com.aspose.slides/icomment) - คอมเมนต์ที่เพิ่มแล้ว

### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

เพิ่มคอมเมนต์สมัยใหม่ใหม่ที่ส่วนท้ายของคอลเลกชัน

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความธรรมดาของคอมเมนต์สมัยใหม่ใหม่ |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ในงานนำเสนอที่ต้องการเพิ่มคอมเมนต์สมัยใหม่ใหม่ |
| shape | [IShape](../../com.aspose.slides/ishape) | รูปร่างบนสไลด์ที่คอมเมนต์สมัยใหม่ใหม่จะเชื่อมโยง |
| position | android.graphics.PointF | ตำแหน่งบนสไลด์ที่ต้องการเพิ่มคอมเมนต์สมัยใหม่ใหม่ |
| creationTime | java.util.Date | เวลาที่สร้างคอมเมนต์สมัยใหม่ |

**คืนค่า:**
[IModernComment](../../com.aspose.slides/imoderncomment) - คอมเมนต์สมัยใหม่ที่เพิ่มแล้ว

### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

แทรกคอมเมนต์ใหม่ลงในคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งขององค์ประกอบในคอลเลกชันที่ต้องการแทรกคอมเมนต์ |
| text | java.lang.String | ข้อความธรรมดาของคอมเมนต์ใหม่ |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ในงานนำเสนอที่ต้องการเพิ่มคอมเมนต์ใหม่ |
| position | android.graphics.PointF | ตำแหน่งบนสไลด์ที่ต้องการเพิ่มคอมเมนต์ใหม่ |
| creationTime | java.util.Date | เวลาที่สร้างคอมเมนต์ |

**คืนค่า:**
[IComment](../../com.aspose.slides/icomment) - คอมเมนต์ที่แทรกแล้ว

### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

แทรกคอมเมนต์สมัยใหม่ใหม่ลงในคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งขององค์ประกอบในคอลเลกชันที่ต้องการแทรกคอมเมนต์สมัยใหม่ |
| text | java.lang.String | ข้อความธรรมดของคอมเมนต์สมัยใหม่ใหม่ |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ในงานนำเสนอที่ต้องการเพิ่มคอมเมนต์สมัยใหม่ใหม่ |
| shape | [IShape](../../com.aspose.slides/ishape) | รูปร่างบนสไลด์ที่คอมเมนต์สมัยใหม่ใหม่จะเชื่อมโยง |
| position | android.graphics.PointF | ตำแหน่งบนสไลด์ที่ต้องการเพิ่มคอมเมนต์สมัยใหม่ใหม่ |
| creationTime | java.util.Date | เวลาที่สร้างคอมเมนต์สมัยใหม่ |

**คืนค่า:**
[IModernComment](../../com.aspose.slides/imoderncomment) - คอมเมนต์สมัยใหม่ที่แทรกแล้ว

### toArray() {#toArray--}
```
public final IComment[] toArray()
```

สร้างและคืนค่าอาร์เรย์ที่มีคอมเมนต์ทั้งหมด

**คืนค่า:**
com.aspose.slides.IComment[] - อาร์เรย์ของ [Comment](../../com.aspose.slides/comment)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

สร้างและคืนค่าอาร์เรย์ที่มีคอมเมนต์ทั้งหมดจากช่วงที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| startIndex | int | ตำแหน่งของคอมเมนต์แรกที่ต้องการคืนค่า |
| count | int | จำนวนคอมเมนต์ที่ต้องการคืนค่า |

**คืนค่า:**
com.aspose.slides.IComment[] - อาร์เรย์ของ [Comment](../../com.aspose.slides/comment)

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่เริ่มจากศูนย์ขององค์ประกอบที่ต้องการลบ |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

ลบการเกิดครั้งแรกของคอมเมนต์ที่ระบุในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | คอมเมนต์ที่ต้องการลบออกจากคอลเลกชัน |

### clear() {#clear--}
```
public final void clear()
```

ลบคอมเมนต์ทั้งหมดออกจากคอลเลกชัน

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

คืนค่า enumerator ที่ทำการวนลูปผ่านคอลเลกชัน

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - IGenericEnumerator ที่ใช้วนลูปผ่านคอลเลกชัน

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด

### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

ค้นหาคอมเมนต์ในคอลเลกชันโดยใช้ตำแหน่ง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| idx | int | ตำแหน่งเฉพาะของคอมเมนต์ที่ต้องการค้นหา  int  |

**คืนค่า:**
[IComment](../../com.aspose.slides/icomment) - คอมเมนต์ที่พบหรือ null [IComment](../../com.aspose.slides/icomment)

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย |
| index | int | ตำแหน่งเริ่มต้นในอาร์เรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันนี้เป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว  boolean .

**คืนค่า:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่า synchronization root อ่านอย่างเดียว  Object .

**คืนค่า:**
java.lang.Object