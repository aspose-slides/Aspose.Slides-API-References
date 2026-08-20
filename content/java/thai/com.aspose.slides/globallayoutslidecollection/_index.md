---
title: GlobalLayoutSlideCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นคอลเลกชันของเลย์เอาต์สไลด์ทั้งหมดในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/globallayoutslidecollection/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**อินเทอร์เฟซที่นำมาใช้ทั้งหมด:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

เป็นคอลเลกชันของเลย์เอาต์สไลด์ทั้งหมดในงานนำเสนอ ขยายคลาส LayoutSlideCollection ด้วยเมธอดสำหรับเพิ่ม/คัดลอกเลย์เอาต์สไลด์ในบริบทของการรวมคอลเลกชันเลย์เอาต์ของมาสเตอร์สไลด์แต่ละชุด

## เมธอด

| Method | Description |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | เพิ่มสำเนาของเลย์เอาต์สไลด์ที่ระบุลงในงานนำเสนอ |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | เพิ่มสำเนาของเลย์เอาต์สไลด์ที่ระบุลงในงานนำเสนอ |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | เพิ่มเลย์เอาต์สไลด์ใหม่ลงในงานนำเสนอ |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

เพิ่มสำเนาของเลย์เอาต์สไลด์ที่ระบุลงในงานนำเสนอ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์ที่จะคัดลอก |

--------------------

เมื่อคัดลอกเลย์เอาต์ระหว่างงานนำเสนอที่ต่างกัน มาสเตอร์ของเลย์เอาต์ก็สามารถคัดลอกได้เช่นกันเพื่อคงรูปแบบต้นฉบับ ระบบทะเบียนภายในจะถูกใช้เพื่อติดตามมาสเตอร์ที่คัดลอกโดยอัตโนมัติเพื่อป้องกันการสร้างสำเนามาสเตอร์เดียวกันหลายครั้ง การคัดลอกมาสเตอร์สไลด์ด้วยตนเองจะไม่ได้ถูกป้องกันหรือบันทึก

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่เพิ่ม

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

เพิ่มสำเนาของเลย์เอาต์สไลด์ที่ระบุลงในงานนำเสนอ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์ที่จะคัดลอก |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | มาสเตอร์สไลด์สำหรับเลย์เอาต์ใหม่ |

--------------------

1) เลย์เอาต์ใหม่จะถูกเชื่อมโยงกับมาสเตอร์ที่กำหนดในงานนำเสนอปลายทาง ดังนั้นนี่เป็นเทียบเคียงกับการคัดลอก/วางโดยใช้ตัวเลือก "Use Destination Theme" ใน PowerPoint  
2) เทียบเคียงของเมธอดนี้คือเมธอด [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) ที่เข้าถึงผ่านคุณสมบัติ ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides))

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่เพิ่ม

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

เพิ่มเลย์เอาต์สไลด์ใหม่ลงในงานนำเสนอ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | มาสเตอร์สไลด์สำหรับเลย์เอ็ตใหม่ |
| layoutType | byte | ประเภทเลย์เอาต์สำหรับเลย์เอาต์ใหม่ ประเภทเลย์เอาต์ที่รองรับ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. ประเภทเลย์เอาต์อื่น ๆ ไม่รองรับในขณะนี้: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject |
| layoutName | java.lang.String | ชื่อของเลย์เอาต์ใหม่ หากชื่อที่ส่งเข้ามามีการใช้งานอยู่แล้วจะเกิด ArgumentException หากพารามิเตอร์เป็น null ชื่อจะถูกสร้างอัตโนมัติตามประเภทเลย์เอาต์ที่ส่งเข้ามา (เช่น "Title Slide" หรือ "1_Title Slide", "2_..", เป็นต้น) |

--------------------

1) เลย์เอาต์ที่เพิ่มสำหรับค่า SlideLayoutType.Custom ของ layoutType จะไม่มีตัวแทนและไม่มีรูปทรงใด ๆ 2) เทียบเคียงของเมธอดนี้คือเมธอด [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) ที่เข้าถึงผ่านคุณสมบัติ ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides))

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - สไลด์ที่เพิ่ม