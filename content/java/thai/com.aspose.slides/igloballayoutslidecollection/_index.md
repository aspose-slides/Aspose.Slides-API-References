---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: แทนชุดของสไลด์เลเอาต์ทั้งหมดในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/igloballayoutslidecollection/
---
**ทุกอินเทอร์เฟซที่นำไปใช้งาน:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

เป็นคอลเลกชันของสไลด์เค้าโครงทั้งหมดในงานนำเสนอ ขยายอินเทอร์เฟซ ILayoutSlideCollection ด้วยเมธอดสำหรับการเพิ่ม/สำเนาเค้าโครงสไลด์ในบริบทของการรวมคอลเลกชันเค้าโครงสไลด์ของมาสเตอร์ที่แตกต่างกัน
## วิธีการ

| Method | Description |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | เพิ่มสำเนาของสไลด์เค้าโครงที่ระบุลงในงานนำเสนอ |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | เพิ่มสำเนาของสไลด์เค้าโครงที่ระบุลงในงานนำเสนอ |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | เพิ่มสไลด์เค้าโครงใหม่ลงในงานนำเสนอ |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

เพิ่มสำเนาของสไลด์เค้าโครงที่ระบุลงในงานนำเสนอ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์ที่จะทำสำเนา |

--------------------

เมื่อทำการสำเนาเค้าโครงระหว่างงานนำเสนอที่แตกต่างกัน มาสเตอร์ของเค้าโครงอาจถูกสำเนาเพื่อคงรูปแบบของแหล่งต้นฉบับ ระบบทะเบียนภายในจะใช้เพื่อติดตามมาสเตอร์ที่ถูกสำเนาอัตโนมัติ เพื่อป้องกันการสร้างสำเนาซ้ำของมาสเตอร์สไลด์เดียวกัน การสำเนามาสเตอร์สไลด์ด้วยตนเองจะไม่ได้ถูกป้องกันหรือบันทึก

**ผลลัพธ์:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่เพิ่ม
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

เพิ่มสำเนาของสไลด์เค้าโครงที่ระบุลงในงานนำเสนอ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์ที่จะทำสำเนา |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | สไลด์มาสเตอร์สำหรับเค้าโครงใหม่ |

--------------------

เค้าโครงใหม่จะเชื่อมโยงกับมาสเตอร์ที่กำหนดในงานนำหมายปลายทาง ดังนั้นจึงเป็นแนวคิดคล้ายการคัดลอก/วางพร้อมตัวเลือก "Use Destination Theme" ใน PowerPoint

**ผลลัพธ์:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่เพิ่ม
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

เพิ่มสไลด์เค้าโครงใหม่ลงในงานนำเสนอ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | สไลด์มาสเตอร์สำหรับเค้าโครงใหม่ |
| layoutType | byte | ประเภทเค้าโครงสำหรับเค้าโครงใหม่ ประเภทเค้าโครงที่รองรับ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. ประเภทเค้าโครงอื่น ๆ ที่ยังไม่รองรับ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject |
| layoutName | java.lang.String | ชื่อสำหรับเค้าโครงใหม่ หากชื่อที่ส่งเข้ามาใช้งานอยู่แล้วจะเกิด ArgumentException หากส่งค่า null จะทำการสร้างชื่ออัตโนมัติตามประเภทเค้าโครงที่ส่ง (เช่น "Title Slide" หรือ "1_Title Slide", "2_.." เป็นต้น) |

--------------------

1) เค้าโครงที่เพิ่มสำหรับค่า SlideLayoutType.Custom ของ layoutType จะไม่มีตัวแทนและไม่มีรูปทรง 2) แนวคิดคล้ายของเมธอดนี้คือเมธอด [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) ที่เข้าถึงผ่านคุณสมบัติ ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides))

**ผลลัพธ์:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่เพิ่ม