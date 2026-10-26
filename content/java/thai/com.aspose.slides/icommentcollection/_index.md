---
title: ICommentCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงคอลเลกชันของความคิดเห็นจากผู้เขียนหนึ่งคน.
type: docs
url: /th/com.aspose.slides/icommentcollection/
---
**ทั้งหมดที่ทำตามอินเทอร์เฟซ:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

เป็นคอลเลกชันของความคิดเห็นจากผู้เขียนหนึ่งคน.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงเอาองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | เพิ่มความคิดเห็นใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | เพิ่มความคิดเห็นสมัยใหม่ใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | แทรกความคิดเห็นใหม่เข้าในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | แทรกความคิดเห็นสมัยใหม่ใหม่เข้าในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [toArray()](#toArray--) | สร้างและคืนค่าอาร์เรย์ที่มีความคิดเห็นทั้งหมด. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | สร้างและคืนค่าอาร์เรย์ที่มีความคิดเห็นทั้งหมดจากช่วงที่ระบุ. |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | ลบการปรากฏครั้งแรกของความคิดเห็นที่ระบุในคอลเลกชัน. |
| [clear()](#clear--) | ลบความคิดเห็นทั้งหมดจากคอลเลกชัน. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```

ดึงองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IComment](../../com.aspose.slides/icomment).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

เพิ่มความคิดเห็นใหม่ที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| text | java.lang.String | ข้อความธรรมดาของความคิดเห็นใหม่. |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ในงานนำเสนอที่ต้องการเพิ่มความคิดเห็นใหม่. |
| position | java.awt.geom.Point2D.Float | ตำแหน่งบนสไลด์ที่ต้องการเพิ่มความคิดเห็นใหม่. |
| creationTime | java.util.Date | เวลาที่สร้างความคิดเห็น. |

**ผลลัพธ์:**
[IComment](../../com.aspose.slides/icomment) - ความคิดเห็นที่เพิ่ม
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

เพิ่มความคิดเห็นสมัยใหม่ใหม่ที่ส่วนท้ายของคอลเลกชัน.

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
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| text | java.lang.String | ข้อความธรรมดของความคิดเห็นสมัยใหม่ใหม่. |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ในงานนำเสนอที่ต้องการเพิ่มความคิดเห็นสมัยใหม่ใหม่. |
| shape | [IShape](../../com.aspose.slides/ishape) | รูปร่างบนสไลด์ที่เชื่อมโยงกับความคิดเห็นสมัยใหม่ใหม่. |
| position | java.awt.geom.Point2D.Float | ตำแหน่งบนสไลด์ที่ต้องการเพิ่มความคิดเห็นสมัยใหม่ใหม่. |
| creationTime | java.util.Date | เวลาที่สร้างความคิดเห็นสมัยใหม่. |

**ผลลัพธ์:**
[IModernComment](../../com.aspose.slides/imoderncomment) - ความคิดเห็นสมัยใหม่ที่เพิ่ม
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

แทรกความคิดเห็นใหม่เข้าในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| index | int | ดัชนีขององค์ประกอบในคอลเลกชันที่ต้องการแทรกความคิดเห็น. |
| text | java.lang.String | ข้อความธรรมดของความคิดเห็นใหม่. |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ในงานนำเสนอที่ต้องการเพิ่มความคิดเห็นใหม่. |
| position | java.awt.geom.Point2D.Float | ตำแหน่งบนสไลด์ที่ต้องการเพิ่มความคิดเห็นใหม่. |
| creationTime | java.util.Date | เวลาที่สร้างความคิดเห็น. |

**ผลลัพธ์:**
[IComment](../../com.aspose.slides/icomment) - ความคิดเห็นที่แทรก
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

แทรกความคิดเห็นสมัยใหม่ใหม่เข้าในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| index | int | ดัชนีขององค์ประกอบในคอลเลกชันที่ต้องการแทรกความคิดเห็นสมัยใหม่. |
| text | java.lang.String | ข้อความธรรมดของความคิดเห็นสมัยใหม่ใหม่. |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์ในงานนำเสนอที่ต้องการเพิ่มความคิดเห็นสมัยใหม่ใหม่. |
| shape | [IShape](../../com.aspose.slides/ishape) | รูปร่างบนสไลด์ที่เชื่อมโยงกับความคิดเห็นสมัยใหม่ใหม่. |
| position | java.awt.geom.Point2D.Float | ตำแหน่งบนสไลด์ที่ต้องการเพิ่มความคิดเห็นสมัยใหม่ใหม่. |
| creationTime | java.util.Date | เวลาที่สร้างความคิดเห็นสมัยใหม่. |

**ผลลัพธ์:**
[IModernComment](../../com.aspose.slides/imoderncomment) - ความคิดเห็นสมัยใหม่ที่แทรก
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

สร้างและคืนค่าอาร์เรย์ที่มีความคิดเห็นทั้งหมด.

**ผลลัพธ์:**
com.aspose.slides.IComment[] - อาร์เรย์ของ [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

สร้างและคืนค่าอาร์เรย์ที่มีความคิดเห็นทั้งหมดจากช่วงที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| startIndex | int | ดัชนีของความคิดเห็นแรกที่ต้องการคืนค่า. |
| count | int | จำนวนความคิดเห็นที่ต้องการคืนค่า. |

**ผลลัพธ์:**
com.aspose.slides.IComment[] - อาร์เรย์ของ [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| index | int | ดัชนีศูนย์ฐานขององค์ประกอบที่ต้องการลบ. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

ลบการปรากฏครั้งแรกของความคิดเห็นที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | ความคิดเห็นที่ต้องการลบออกจากคอลเลกชัน. |

### clear() {#clear--}
```
public abstract void clear()
```

ลบความคิดเห็นทั้งหมดจากคอลเลกชัน.