---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงคอลเลกชันของสไลด์เค้าโครงทั้งหมดในงานนำเสนอ
type: docs
url: /th/com.aspose.slides/globallayoutslidecollection/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**อินเตอร์เฟซที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)  
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

แสดงคอลเล็กชันของสไลด์เค้าโครงทั้งหมดในงานนำเสนอ สืบทอดคลาส LayoutSlideCollection พร้อมเมธอดสำหรับการเพิ่ม/ทำสำเนาเค้าโครงสไลด์ในบริบทของการรวมคอลเล็กชันเค้าโครงของมาสเตอร์สไลด์แต่ละรายการ

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | เพิ่มสำเนาของเค้าโครงสไลด์ที่ระบุลงในงานนำเสนอ |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | เพิ่มสำเนาของเค้าโครงสไลด์ที่ระบุลงในงานนำเสนอ |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | เพิ่มเค้าโครงสไลด์ใหม่ลงในงานนำเสนอ |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

เพิ่มสำเนาของเค้าโครงสไลด์ที่ระบุลงในงานนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์ที่จะทำสำเนา |

--------------------

เมื่อทำการคัดลอกเค้าโครงระหว่างงานนำเสนอที่ต่างกัน มาสเตอร์ของเค้าโครงอาจถูกคัดลอกด้วยเพื่อคงรูปแบบต้นฉบับ ระบบทะเบียนภายในจะใช้เพื่อติดตามมาสเตอร์ที่ถูกคัดลอกโดยอัตโนมัติ เพื่อป้องกันการสร้างสำเนามาสเตอร์สไลด์เดียวกันหลายครั้ง การคัดลอกมาสเตอร์สไลด์ด้วยตนเองจะไม่ถูกป้องกันหรือบันทึกไว้

**ผลลัพธ์:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่เพิ่ม

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

เพิ่มสำเนาของเค้าโครงสไลด์ที่ระบุลงในงานนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์ที่จะทำสำเนา |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | มาสเตอร์สไลด์สำหรับเค้าโครงใหม่ |

--------------------

1) เค้าโครงใหม่จะเชื่อมโยงกับมาสเตอร์ที่กำหนดในงานนำหมายปลายทาง นั่นคือการทำสำเนา/วางพร้อมตัวเลือก “Use Destination Theme” ใน PowerPoint  
2) วิธีการที่คล้ายกับเมธอดนี้คือเมธอด [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) ที่เข้าถึงด้วยพร็อพเพอร์ตี้ ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides))

**ผลลัพธ์:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่เพิ่ม

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

เพิ่มเค้าโครงสไลด์ใหม่ลงในงานนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | มาสเตอร์สไลด์สำหรับเค้าโครงใหม่ |
| layoutType | byte | ประเภทเค้าโครงสำหรับเค้าโครงใหม่ ประเภทเค้าโครงที่รองรับ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. ประเภทเค้าโครงอื่น ๆ ยังไม่รองรับ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject |
| layoutName | java.lang.String | ชื่อสำหรับเค้าโครงใหม่ หากชื่อที่ส่งเข้ามาใช้งานอยู่แล้วจะโยน ArgumentException หากส่งค่า null จะสร้างชื่อโดยอัตโนมัติตามประเภทเค้าโครงที่ส่ง (เช่น “Title Slide” หรือ “1_Title Slide”, “2_..” เป็นต้น) |

--------------------

1) เค้าโครงที่เพิ่มสำหรับค่า SlideLayoutType.Custom ของ layoutType จะไม่มีตัวแสดงตำแหน่งและไม่มีรูปร่างใด ๆ  
2) วิธีการที่คล้ายกับเมธอดนี้คือเมธอด [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) ที่เข้าถึงด้วยพร็อพเพอร์ตี้ ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides))

**ผลลัพธ์:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่เพิ่ม