---
title: CommentCollection
second_title: อ้างอิง API Aspose.Slides สำหรับ Java
description: แสดงถึงคอลเลกชันของความคิดเห็นของผู้เขียนคนเดียว.
type: docs
url: /th/com.aspose.slides/commentcollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

แสดงถึงคอลเลกชันของความคิดเห็นของผู้เขียนคนเดียว.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | รับจำนวนขององค์ประกอบที่อยู่ในคอลเลกชันจริงๆ |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่กำหนด |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | เพิ่มความคิดเห็นใหม่ที่ท้ายของคอลเลกชัน |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | เพิ่มความคิดเห็นสมัยใหม่ใหม่ที่ท้ายของคอลเลกชัน |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | แทรกความคิดเห็นใหม่เข้าสู่คอลเลกชันที่ตำแหน่งที่กำหนด |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | แทรกความคิดเห็นสมัยใหม่ใหม่เข้าสู่คอลเลกชันที่ตำแหน่งที่กำหนด |
| [toArray()](#toArray--) | สร้างและคืนอาเรย์ที่มีความคิดเห็นทั้งหมด |
| [toArray(int startIndex, int count)](#toArray-int-int-) | สร้างและคืนอาเรย์ที่มีความคิดเห็นทั้งหมดจากช่วงที่กำหนด |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่กำหนดในคอลเลกชัน |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | ลบการเกิดครั้งแรกของความคิดเห็นที่ระบุในคอลเลกชัน |
| [clear()](#clear--) | ลบความคิดเห็นทั้งหมดจากคอลเลกชัน |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | ค้นหาความคิดเห็นในคอลเลกชันตามตำแหน่ง |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากของการซิงโครไนซ์ |

### size() {#size--}
```
public final int size()
```

รับจำนวนขององค์ประกอบที่อยู่ในคอลเลกชันจริงๆ อ่านอย่างเดียว  int .

**คืนค่า:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่กำหนด อ่านอย่างเดียว [Comment](../../com.aspose.slides/comment).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IComment](../../com.aspose.slides/icomment)

### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

เพิ่มความคิดเห็นใหม่ที่ท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความปกติของความคิดเห็นใหม่ |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ในงานนำเสนอที่เพิ่มความคิดเห็นใหม่ |
| position | java.awt.geom.Point2D.Float | ตำแหน่งบนสไลด์ที่เพิ่มความคิดเห็นใหม่ |
| creationTime | java.util.Date | เวลาการสร้างความคิดเห็น |

**คืนค่า:**
[IComment](../../com.aspose.slides/icomment) - ความคิดเห็นที่เพิ่ม

### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

เพิ่มความคิดเห็นสมัยใหม่ใหม่ที่ท้ายของคอลเลกชัน.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความปกติของความคิดเห็นสมัยใหม่ใหม่ |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ในงานนำเสนอที่เพิ่มความคิดเห็นสมัยใหม่ใหม่ |
| shape | [IShape](../../com.aspose.slides/ishape) | รูปร่างบนสไลด์ที่เชื่อมโยงกับความคิดเห็นสมัยใหม่ใหม่ |
| position | java.awt.geom.Point2D.Float | ตำแหน่งบนสไลด์ที่เพิ่มความคิดเห็นสมัยใหม่ใหม่ |
| creationTime | java.util.Date | เวลาการสร้างความคิดเห็นสมัยใหม่ |

**คืนค่า:**
[IModernComment](../../com.aspose.slides/imoderncomment) - ความคิดเห็นสมัยใหม่ที่เพิ่ม

### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

แทรกความคิดเห็นใหม่เข้าสู่คอลเลกชันที่ตำแหน่งที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งขององค์ประกอบในคอลเลกชันที่ต้องการแทรกความคิดเห็น |
| text | java.lang.String | ข้อความปกติของความคิดเห็นใหม่ |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ในงานนำเสนอที่เพิ่มความคิดเห็นใหม่ |
| position | java.awt.geom.Point2D.Float | ตำแหน่งบนสไลด์ที่เพิ่มความคิดเห็นใหม่ |
| creationTime | java.util.Date | เวลาการสร้างความคิดเห็น |

**คืนค่า:**
[IComment](../../com.aspose.slides/icomment) - ความคิดเห็นที่แทรก

### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

แทรกความคิดเห็นสมัยใหม่ใหม่เข้าสู่คอลเลกชันที่ตำแหน่งที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งขององค์ประกอบในคอลเลกชันที่ต้องการแทรกความคิดเห็นสมัยใหม่ |
| text | java.lang.String | ข้อความปกติของความคิดเห็นสมัยใหม่ใหม่ |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ในงานนำเสนอที่เพิ่มความคิดเห็นสมัยใหม่ใหม่ |
| shape | [IShape](../../com.aspose.slides/ishape) | รูปร่างบนสไลด์ที่เชื่อมโยงกับความคิดเห็นสมัยใหม่ใหม่ |
| position | java.awt.geom.Point2D.Float | ตำแหน่งบนสไลด์ที่เพิ่มความคิดเห็นสมัยใหม่ใหม่ |
| creationTime | java.util.Date | เวลาการสร้างความคิดเห็นสมัยใหม่ |

**คืนค่า:**
[IModernComment](../../com.aspose.slides/imoderncomment) - ความคิดเห็นสมัยใหม่ที่แทรก

### toArray() {#toArray--}
```
public final IComment[] toArray()
```

สร้างและคืนอาเรย์ที่มีความคิดเห็นทั้งหมด.

**คืนค่า:**
com.aspose.slides.IComment[] - อาเรย์ของ [Comment](../../com.aspose.slides/comment).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

สร้างและคืนอาเรย์ที่มีความคิดเห็นทั้งหมดจากช่วงที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| startIndex | int | ดัชนีของความคิดเห็นแรกที่จะคืน |
| count | int | จำนวนความคิดเห็นที่จะคืน |

**คืนค่า:**
com.aspose.slides.IComment[] - อาเรย์ของ [Comment](../../com.aspose.slides/comment).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งที่กำหนดในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นที่ศูนย์ขององค์ประกอบที่จะลบ |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

ลบการเกิดครั้งแรกของความคิดเห็นที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | ความคิดเห็นที่ต้องการลบจากคอลเลกชัน |

### clear() {#clear--}
```
public final void clear()
```

ลบความคิดเห็นทั้งหมดจากคอลเลกชัน.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - IGenericEnumerator ที่สามารถใช้เพื่อวนซ้ำผ่านคอลเลกชัน

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด

### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

ค้นหาความคิดเห็นในคอลเลกชันตามตำแหน่ง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| idx | int | ดัชนีที่ไม่ซ้ำของความคิดเห็นที่ต้องการค้นหา  int . |

**คืนค่า:**
[IComment](../../com.aspose.slides/icomment) - ความคิดเห็นที่พบหรือ null [IComment](../../com.aspose.slides/icomment)

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาเรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว  boolean .

**คืนค่า:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่ารากของการซิงโครไนซ์ อ่านอย่างเดียว  Object .

**คืนค่า:**
java.lang.Object