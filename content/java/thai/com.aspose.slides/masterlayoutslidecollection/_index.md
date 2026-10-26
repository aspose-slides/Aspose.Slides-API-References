---
title: MasterLayoutSlideCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงคอลเลกชันของสไลด์เค้าโครงทั้งหมดของมาสเตอร์สไลด์ที่กำหนดไว้.
type: docs
url: /th/com.aspose.slides/masterlayoutslidecollection/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**All Implemented Interfaces:**  
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)  
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

แสดงถึงคอลเลกชันของสไลด์เค้าโครงทั้งหมดของมาสเตอร์สไลด์ที่กำหนดไว้ ขยายคลาส LayoutSlideCollection พร้อมเมธอดสำหรับการเพิ่ม/แทรก/ลบ/ทำสำเนา/จัดเรียงสไลด์เค้าโครงในบริบทของคอลเลกชันสไลด์เค้าโครงของมาสเตอร์แต่ละอัน

## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | เพิ่มสำเนาของสไลด์เค้าโครงที่กำหนดไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | แทรกสำเนาของสไลด์เค้าโครงที่กำหนดไปยังตำแหน่งที่ระบุของคอลเลกชัน |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | เพิ่มสไลด์เค้าโครงใหม่ไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | แทรกสไลด์เค้าโครงใหม่ไปยังตำแหน่งที่ระบุของคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | ย้ายสไลด์เค้าโครงจากคอลเลกชันไปยังตำแหน่งที่ระบุ |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

เพิ่มสำเนาของสไลด์เค้าโครงที่กำหนดไปยังตำแหน่งสุดท้ายของคอลเลกชัน

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์ที่จะทำสำเนา |

--------------------

1) เค้าโครงใหม่จะเชื่อมโยงกับมาสเตอร์สไลด์แม่สำหรับคอลเลกชันสไลด์เค้าโครงนี้ ดังนั้นจึงเป็นการทำสำเนา/วางแบบมีตัวเลือก “Use Destination Theme” ใน PowerPoint  
2) วิธีการที่คล้ายกันคือเมธอด [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) ที่เข้าถึงด้วย property ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides))

**Returns:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่เพิ่ม

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

แทรกสำเนาของสไลด์เค้าโครงที่กำหนดไปยังตำแหน่งที่ระบุของคอลเลกชัน

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่ |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์ที่จะทำสำเนา |

--------------------

เค้าโครงใหม่จะเชื่อมโยงกับมาสเตอร์สไลด์แม่สำหรับคอลเลกชันสไลด์เค้าโครงนี้ ดังนั้นจึงเป็นการทำสำเนา/วางแบบมีตัวเลือก “Use Destination Theme” ใน PowerPoint

**Returns:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่แทรก

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

เพิ่มสไลด์เค้าโครงใหม่ไปยังตำแหน่งสุดท้ายของคอลเลกชัน

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| layoutType | byte | ประเภทเค้าโครงสำหรับเค้าโครงใหม่ ประเภทที่รองรับ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. ประเภทอื่น ๆ ไม่รองรับในขณะนี้: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject |
| layoutName | java.lang.String | ชื่อสำหรับเค้าโครงใหม่ หากชื่อที่ระบุอยู่ในใช้แล้วจะเกิด ArgumentException หากส่งค่า null จะสร้างชื่ออัตโนมัติตามประเภทเค้าโครงที่ระบุ (เช่น “Title Slide” หรือ “1\_Title Slide”, “2\_..” ฯลฯ) |

--------------------

1) เค้าโครงที่เพิ่มสำหรับค่า SlideLayoutType.Custom ของ layoutType จะไม่มีตัวแปรแทนหรือรูปร่างใด ๆ  
2) วิธีการที่คล้ายกันคือเมธอด [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) ที่เข้าถึงด้วย property ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides))

**Returns:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่เพิ่ม

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

แทรกสไลด์เค้าโครงใหม่ไปยังตำแหน่งที่ระบุของคอลเลกชัน

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่ |
| layoutType | byte | ประเภทเค้าโครงสำหรับเค้าโครงใหม่ ประเภทที่รองรับ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. ประเภทอื่น ๆ ไม่รองรับในขณะนี้: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject |
| layoutName | java.lang.String | ชื่อสำหรับเค้าโครงใหม่ หากชื่อที่ระบุอยู่ในใช้แล้วจะเกิด ArgumentException หากส่งค่า null จะสร้างชื่ออัตโนมัติตามประเภทเค้าโครงที่ระบุ (เช่น “Title Slide” หรือ “1\_Title Slide”, “2\_..” ฯลฯ) |

--------------------

เค้าโครงที่แทรกสำหรับค่า SlideLayoutType.Custom ของ layoutType จะไม่มีตัวแปรแทนหรือรูปร่างใด ๆ

**Returns:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่แทรก

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ขององค์ประกอบที่จะลบ |

--------------------

1) เพื่อลดความเสี่ยงของการโยน PptxEditException ให้ตรวจสอบ property HasDependingSlides ของเค้าโครงก่อนที่จะลบ  
2) คุณสามารถใช้เมธอด [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) เพื่อทำให้โค้ดง่ายขึ้น

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

ย้ายสไลด์เค้าโครงจากคอลเลกชันไปยังตำแหน่งที่ระบุ

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเป้าหมาย |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์ที่จะย้าย |