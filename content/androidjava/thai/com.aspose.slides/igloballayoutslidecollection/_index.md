---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงคอลเลกชันของสไลด์เค้าโครงทั้งหมดในงานนำเสนอ
type: docs
url: /th/com.aspose.slides/igloballayoutslidecollection/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

เป็นคอลเลกชันของสไลด์เค้าโครงทั้งหมดในงานนำเสนอ ขยายอินเทอร์เฟซ ILayoutSlideCollection ด้วยเมธอดสำหรับการเพิ่ม/คัดลอกสไลด์เค้าโครงในบริบทของการรวมคอลเลกชันแยกของสไลด์เค้าโครงมาสเตอร์

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | เพิ่มสำเนาของสไลด์เค้าโครงที่ระบุไปยังงานนำเสนอ |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | เพิ่มสำเนาของสไลด์เค้าโครงที่ระบุไปยังงานนำเสนอ |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | เพิ่มสไลด์เค้าโครงใหม่ไปยังงานนำเสนอ |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


เพิ่มสำเนาของสไลด์เค้าโครงที่ระบุไปยังงานนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์ที่ต้องการคัดลอก |

--------------------

เมื่อคัดลอกเค้าโครงระหว่างงานนำเสนอที่แตกต่างกัน มาสเตอร์ของเค้าโครงก็สามารถคัดลอกได้เช่นกันเพื่อคงรูปแบบต้นฉบับ ระบบทะเบียนภายในจะใช้เพื่อจับตามมาสเตอร์ที่ถูกคัดลอกโดยอัตโนมัติเพื่อป้องกันการสร้างสำเนาซ้ำของมาสเตอร์สไลด์เดียวกัน การคัดลอกมาสเตอร์สไลด์ด้วยตนเองจะไม่ถูกป้องกันหรือบันทึก

**คืนค่า:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่เพิ่ม

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


เพิ่มสำเนาของสไลด์เค้าโครงที่ระบุไปยังงานนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์ที่ต้องการคัดลอก |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | มาสเตอร์สไลด์สำหรับเค้าโครงใหม่ |

--------------------

เค้าโครงใหม่จะถูกเชื่อมโยงกับมาสเตอร์ที่กำหนดในงานนำหมายปลายทาง ดังนั้นจึงเป็นการทำงานที่คล้ายกับคัดลอก/วางพร้อมตัวเลือก “ใช้ธีมปลายทาง” ใน PowerPoint

**คืนค่า:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่เพิ่ม

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


เพิ่มสไลด์เค้าโครงใหม่ไปยังงานนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | มาสเตอร์สไลด์สำหรับเค้าโครงใหม่ |
| layoutType | byte | ชนิดเค้าโครงสำหรับเค้าโครงใหม่ ชนิดเค้าโครงที่รองรับ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. ชนิดเค้าโครงอื่น ๆ ที่ไม่รองรับในขณะนี้: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject |
| layoutName | java.lang.String | ชื่อสำหรับเค้าโครงใหม่ หากชื่อที่ส่งเข้ามาใช้แล้วอยู่แล้ว จะเกิด ArgumentException หากพารามิเตอร์เป็น null จะสร้างชื่ออัตโนมัติตามชนิดเค้าโครงที่ส่งเข้ามา (เช่น “Title Slide” หรือ “1_Title Slide”, “2_..” เป็นต้น) |

--------------------

1) เค้าโครงที่เพิ่มสำหรับค่า SlideLayoutType.Custom ของ layoutType จะไม่มีตัวแทนที่วางไว้และไม่มีรูปร่าง 2) วิธีการที่คล้ายกันของเมธอดนี้คือเมธอด [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) ที่เข้าถึงได้ผ่านคุณสมบัติ ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides))

**คืนค่า:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่เพิ่ม