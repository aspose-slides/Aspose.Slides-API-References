---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: เป็นตัวแทนของการรวบรวมสไลด์เลย์เอาต์ทั้งหมดของมาสเตอร์สไลด์ที่กำหนด
type: docs
url: /th/com.aspose.slides/masterlayoutslidecollection/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

เป็นตัวแทนของการรวบรวมสไลด์เลย์เอาต์ทั้งหมดของมาสเตอร์สไลด์ที่กำหนดไว้. ขยายคลาส LayoutSlideCollection ด้วยเมธอดสำหรับการเพิ่ม/แทรก/ลบ/ทำสำเนา/จัดลำดับใหม่ของสไลด์เลย์เอาต์ในบริบทของคอลเลกชันแต่ละชุดของสไลด์เลย์เอาต์ของมาสเตอร์สไลด์.

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | เพิ่มสำเนาของสไลด์เลย์เอาต์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | แทรกสำเนาของสไลด์เลย์เอาต์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | เพิ่มสไลด์เลย์เอาต์ใหม่ไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | แทรกสไลด์เลย์เอาต์ใหม่ไปยังตำแหน่งที่ระบุของคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่กำหนดของคอลเลกชัน. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | ย้ายสไลด์เลย์เอาต์จากคอลเลกชันไปยังตำแหน่งที่ระบุ. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

เพิ่มสำเนาของสไลด์เลย์เอาต์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์ที่จะทำสำเนา. |

--------------------

1) เลย์เอาต์ใหม่จะถูกเชื่อมโยงกับมาสเตอร์สไลด์พาเรนต์สำหรับคอลเลกชันสไลด์เลย์เอาต์นี้ ดังนั้นจึงเป็นแบบเดียวกับการคัดลอก/วางโดยเลือกตัวเลือก "Use Destination Theme" ใน PowerPoint. 2) แบบเดียวกับเมธอดนี้คือเมธอด [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) ที่เข้าถึงผ่านคุณสมบัติ ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**คืนค่า:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่เพิ่ม.

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

แทรกสำเนาของสไลด์เลย์เอาต์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของสไลด์ใหม่. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์ที่จะทำสำเนา. |

--------------------

เลย์เอาต์ใหม่จะถูกเชื่อมโยงกับมาสเตอร์สไลด์พาเรนต์สำหรับคอลเลกชันสไลด์เลย์เอาต์นี้ ดังนั้นจึงเป็นแบบเดียวกับการคัดลอก/วางโดยเลือกตัวเลือก "Use Destination Theme" ใน PowerPoint.

**คืนค่า:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่แทรก.

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

เพิ่มสไลด์เลย์เอาต์ใหม่ไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| layoutType | byte | ประเภทของเลย์เอาต์สำหรับเลย์เอาต์ใหม่. ประเภทเลย์เอาต์ที่รองรับ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. ประเภทเลย์เอาต์อื่น ๆ ที่ยังไม่รองรับ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | ชื่อสำหรับเลย์เอาต์ใหม่. หากชื่อที่ส่งเข้ามาใช้งานอยู่แล้วจะเกิด ArgumentException. หากพารามิเตอร์เป็น null ชื่อจะถูกสร้างโดยอัตโนมัติตามประเภทเลย์เอาต์ที่ส่งเข้ามา (เช่น "Title Slide" หรือ "1\_Title Slide", "2\_..", เป็นต้น). |

--------------------

1) เลย์เอาต์ที่เพิ่มสำหรับค่า SlideLayoutType.Custom ของ layoutType จะไม่มีตำแหน่งตัวแปรและไม่มีรูปทรง. 2) แบบเดียวกับเมธอดนี้คือเมธอด [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) ที่เข้าถึงผ่านคุณสมบัติ ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**คืนค่า:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่เพิ่ม.

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

แทรกสไลด์เลย์เอาต์ใหม่ไปยังตำแหน่งที่ระบุของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของสไลด์ใหม่. |
| layoutType | byte | ประเภทของเลย์เอาต์สำหรับเลย์เอาต์ใหม่. ประเภทเลย์เอาต์ที่รองรับ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. ประเภทเลย์เอต์อื่น ๆ ที่ยังไม่รองรับ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | ชื่อสำหรับเลย์เอาต์ใหม่. หากชื่อที่ส่งเข้ามาใช้งานอยู่แล้วจะเกิด ArgumentException. หากพารามิเตอร์เป็น null ชื่อจะถูกสร้างโดยอัตโนมัติตามประเภทเลย์เอาต์ที่ส่งเข้ามา (เช่น "Title Slide" หรือ "1\_Title Slide", "2\_..", เป็นต้น). |

--------------------

เลย์เอาต์ที่แทรกสำหรับค่า SlideLayoutType.Custom ของ layoutType จะไม่มีตำแหน่งตัวแปรและไม่มีรูปทรง.

**คืนค่า:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่แทรก.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งที่กำหนดของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีศูนย์ฐานขององค์ประกอบที่ต้องการลบ. |

--------------------

1) เพื่อหลีกเลี่ยงการโยน PptxEditException ควรตรวจสอบคุณสมบัติ HasDependingSlides ของเลย์เอาต์ก่อน. 2) คุณสามารถใช้เมธอด [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) เพื่อทำให้โค้ดง่ายขึ้น.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

ย้ายสไลด์เลย์เอาต์จากคอลเลกชันไปยังตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเป้าหมาย. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์ที่ย้าย. |