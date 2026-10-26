---
title: ShapeCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นคอลเลกชันของรูปร่าง.
type: docs
url: /th/com.aspose.slides/shapecollection/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**ทั้งหมดของอินเทอร์เฟซที่นำไปใช้:**  
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)  
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

แสดงถึงคอลเลกชันของรูปร่าง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | รับจำนวนขององค์ประกอบที่อยู่ในคอลเลกชันจริง. |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลชุดตัวอย่างและการตั้งค่า, แล้วเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลชุดตัวอย่างและการตั้งค่า, แล้วเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | สร้างแผนภาพ SmartArt และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลชุดตัวอย่างและการตั้งค่า, แล้วแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลชุดตัวอย่างและการตั้งค่า, แล้วแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | สร้างกรอบ Zoom ใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | สร้างกรอบ Zoom ใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | สร้างกรอบ Zoom ใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | สร้างกรอบ Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | สร้างกรอบ Section Zoom ใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | สร้างกรอบ Section Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | สร้างกรอบ Section Zoom ใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | สร้างกรอบ Section Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | สร้างกรอบ Summary Zoom ใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | สร้างกรอบ Summary Zoom ใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | สร้างกรอบวัตถุ OLE ใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | สร้างกรอบวัตถุ OLE ใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | สร้างกรอบวัตถุ OLE ใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | สร้างกรอบวัตถุ OLE ใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | สร้างกรอบวิดีโอใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | สร้างกรอบวิดีโอใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | สร้างกรอบวิดีโอใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | สร้างกรอบเสียงใหม่ที่เชื่อมโยงกับแทร็ก CD และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | สร้างกรอบเสียงใหม่ที่เชื่อมโยงกับแทร็ก CD และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | สร้างกรอบเสียงใหม่ที่เชื่อมโยงกับไฟล์เสียงภายนอกและเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | สร้างกรอบเสียงใหม่ที่เชื่อมโยงกับไฟล์เสียงภายนอกและแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | สร้างกรอบเสียงใหม่พร้อมไฟล์ WAV ฝังและเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | สร้างกรอบเสียงใหม่พร้อมไฟล์ WAV ฝังและแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | สร้างกรอบเสียงใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่างโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | สร้างกรอบเสียงใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | คืนค่าดัชนีที่เริ่มจากศูนย์ของการพบครั้งแรกของรูปร่างที่ระบุในคอลเลกชัน. |
| [toArray()](#toArray--) | สร้างและคืนค่าอาเรย์ที่บรรจุรูปร่างทั้งหมด. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | สร้างและคืนค่าอาเรย์ที่บรรจุรูปร่างทั้งหมดในช่วงที่ระบุ. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | ย้ายรูปร่างที่ระบุไปยังตำแหน่งใหม่ภายในคอลเลกชันรูปร่าง. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | ย้ายรูปร่างที่ระบุภายในคอลเลกชันรูปร่าง, วางเริ่มจากดัชนีที่กำหนด. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | สร้างรูปอัตโนมัติใหม่ด้วยการจัดรูปแบบเริ่มต้นและเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | สร้างรูปอัตโนมัติใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง, โดยอาจเริ่มต้นด้วยการจัดรูปแบบแม่แบบเริ่มต้น. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | สร้างรูปสี่เหลี่ยมอัตโนมัติใหม่เพื่อเก็บเนื้อหาทางคณิตศาสตร์และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | สร้างรูปอัตโนมัติใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ, ใช้การจัดรูปแบบแม่แบบเริ่มต้น. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | สร้างรูปอัตโนมัติใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ, โดยอาจเริ่มต้นด้วยสไตล์แม่แบบเริ่มต้น. |
| [addGroupShape()](#addGroupShape--) | สร้างกลุ่มรูปร่างเปล่าใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | สร้างกลุ่มรูปร่างใหม่, แปลงภาพ SVG ที่ระบุเป็นรูปแต่ละรูป, และเพิ่มกลุ่มที่ได้ไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | สร้างกลุ่มรูปร่างเปล่าใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | สร้างรูปเชื่อมต่อใหม่ด้วยสไตล์แม่แบบเริ่มต้นและเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | สร้างรูปเชื่อมต่อใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง, โดยอาจใช้สไตล์แม่แบบเริ่มต้น. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | สร้างรูปเชื่อมต่อใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ, ใช้สไตล์แม่แบบเริ่มต้น. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | สร้างรูปเชื่อมต่อใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ, โดยอาจใช้สไตล์แม่แบบเริ่มต้น. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | สร้างกรอบรูปภาพใหม่ที่บรรจุภาพที่ระบุและเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | สร้างกรอบรูปภาพใหม่ที่บรรจุภาพที่ระบุและแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | สร้างตารางใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | สร้างตารางใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [removeAt(int index)](#removeAt-int-) | ลบรูปร่างที่ตำแหน่งที่ระบุออกจากคอลเลกชันรูปร่าง. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | ลบการพบครั้งแรกของรูปร่างที่ระบุออกจากคอลเลกชันรูปร่าง. |
| [clear()](#clear--) | ลบรูปร่างทั้งหมดออกจากคอลเลกชันรูปร่าง. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [getParentGroup()](#getParentGroup--) | รับวัตถุกลุ่มรูปร่างพาเรนท์สำหรับคอลเลกชันรูปร่าง. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | สร้างสำเนาของรูปร่างที่ระบุและแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | สร้างสำเนาของรูปร่างที่ระบุและแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | สร้างสำเนาของรูปร่างที่ระบุและแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | คืนค่าแสดงว่าเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) หรือไม่. |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากของการซิงโครไนซ์. |

### size() {#size--}
```
public final int size()
```

รับจำนวนขององค์ประกอบที่อยู่ในคอลเลกชันจริง. อ่านอย่างเดียว  int .

**คืนค่า:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IShape](../../com.aspose.slides/ishape).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลชุดตัวอย่างและการตั้งค่า, แล้วเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation ที่แทนไฟล์ PPTX
>  Presentation pres = new Presentation();
>  try {
>      // เข้าถึงสไลด์แรก
>      ISlide sld = pres.getSlides().get_Item(0);
>      // เพิ่มแผนภูมิพร้อมข้อมูลเริ่มต้น
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // ตั้งชื่อหัวข้อของแผนภูมิ
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // ตั้งค่าชุดข้อมูลแรกให้แสดงค่า
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // ตั้งดัชนีสำหรับแผ่นข้อมูลของแผนภูมิ
>      int defaultWorksheetIndex = 0;
>      // รับแผ่นงานข้อมูลของแผนภูมิ
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // ลบชุดข้อมูลและประเภทที่สร้างโดยอัตโนมัติเริ่มต้น
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // เพิ่มชุดข้อมูลใหม่
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // เพิ่มประเภทใหม่
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // ดึงชุดข้อมูลแผนภูมิแรก
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // เติมข้อมูลให้ชุดข้อมูล
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // ตั้งค่าสีเติมสำหรับชุดข้อมูล
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // ดึงชุดข้อมูลแผนภูมิที่สอง
>      series = chart.getChartData().getSeries().get_Item(1);
>      // เติมข้อมูลให้ชุดข้อมูล
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // ตั้งค่าสีเติมสำหรับชุดข้อมูล
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // ตั้งค่าป้ายกำกับแรกให้แสดงชื่อประเภท
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // ตั้งค่าชุดข้อมูลให้แสดงค่าในป้ายกำกับที่สาม
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // บันทึกไฟล์ PPTP ไปยังดิสก์
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | int | ประเภทของแผนภูมิที่ต้องการเพิ่ม. |
| x | float | ค่าพิกัด x ของแผนภูมิใหม่, หน่วยเป็นจุด. |
| y | float | ค่าพิกัด y ของแผนภูมิใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของแผนภูมิ, หน่วยเป็นจุด. |
| height | float | ความสูงของแผนภูมิ, หน่วยเป็นจุด. |

**คืนค่า:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) ที่สร้างใหม่.

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลชุดตัวอย่างและการตั้งค่า, แล้วเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | int | ประเภทของแผนภูมิที่ต้องการเพิ่ม. |
| x | float | ค่าพิกัด x ของแผนภูมิใหม่, หน่วยเป็นจุด. |
| y | float | ค่าพิกัด y ของแผนภูมิใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของแผนภูมิ, หน่วยเป็นจุด. |
| height | float | ความสูงของแผนภูมิ, หน่วยเป็นจุด. |
| initWithSample | boolean | true เพื่อเริ่มต้นแผนภูมิใหม่ด้วยข้อมูลชุดตัวอย่างและการตั้งค่า; false เพื่อสร้างแผนภูมิโดยไม่มีชุดข้อมูลและการตั้งค่าขั้นต่ำ, ซึ่งทำให้การสร้างเร็วขึ้น. |

**คืนค่า:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) ที่สร้างใหม่.

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

สร้างแผนภาพ SmartArt และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง.

--------------------

> ```
> The following example shows how to add smart shape in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | ค่าพิกัด x ของกรอบแผนภาพ, หน่วยเป็นจุด. |
| y | float | ค่าพิกัด y ของกรอบแผนภาพ, หน่วยเป็นจุด. |
| width | float | ความกว้างของกรอบแผนภาพ, หน่วยเป็นจุด. |
| height | float | ความสูงของกรอบแผนภาพ, หน่วยเป็นจุด. |
| layoutType | int | ประเภทเลย์เอาต์ของ SmartArt. |

**คืนค่า:**
[ISmartArt](../../com.aspose.slides/ismartart) - [ISmartArt](../../com.aspose.slides/ismartart) ที่สร้างใหม่.

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลชุดตัวอย่างและการตั้งค่า, แล้วแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | int | ประเภทของแผนภูมิที่ต้องการสร้าง. |
| x | float | ค่าพิกัด x ของแผนภูมิใหม่, หน่วยเป็นจุด. |
| y | float | ค่าพิกัด y ของแผนภูมิใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของแผนภูมิใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของแผนภูมิใหม่, หน่วยเป็นจุด. |
| index | int | ดัชนีเริ่มจากศูนย์ที่ต้องการแทรกแผนภูมิใหม่ในคอลเลกชันรูปร่าง. |

**คืนค่า:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) ที่สร้างใหม่.

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลชุดตัวอย่างและการตั้งค่า, แล้วแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ.
| x | float | พิกัด x ของแผนภูมิใหม่หน่วยเป็นจุด |
| y | float | พิกัด y ของแผนภูมิใหม่หน่วยเป็นจุด |
| width | float | ความกว้างของแผนภูมิใหม่หน่วยเป็นจุด |
| height | float | ความสูงของแผนภูมิใหม่หน่วยเป็นจุด |
| index | int | ดัชนีที่เริ่มจากศูนย์ซึ่งจะใส่แผนภูมิใหม่ลงในคอลเลกชันรูปร่าง |
| initWithSample | boolean | true เพื่อเริ่มต้นแผนภูมิใหม่ด้วยข้อมูลและการตั้งค่าตัวอย่าง; false เพื่อสร้างแผนภูมิโดยไม่มีชุดข้อมูลและตั้งค่าขั้นต่ำเท่านั้น, ซึ่งทำให้การสร้างเร็วขึ้น |

**ผลลัพธ์:**
[IChart](../../com.aspose.slides/ichart) - The newly created [IChart](../../com.aspose.slides/ichart).
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

สร้างเฟรม Zoom ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง.

--------------------

> ```
> ตัวอย่างนี้แสดงการเพิ่มออบเจ็กต์ Zoom ไปที่ส่วนท้ายของคอลเลกชัน
>  (สมมติว่ามีสไลด์อย่างน้อยสองสไลด์ในงานนำเสนอ "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรม Zoom ใหม่หน่วยเป็นจุด |
| y | float | พิกัด y ของเฟรม Zoom ใหม่หน่วยเป็นจุด |
| width | float | ความกว้างของเฟรม Zoom ใหม่หน่วยเป็นจุด |
| height | float | ความสูงของเฟรม Zoom ใหม่หน่วยเป็นจุด |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) ที่อ้างอิงโดยเฟรม Zoom; ต้องเป็นของงานนำเสนอนี้ |

**ผลลัพธ์:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - The newly created [IZoomFrame](../../com.aspose.slides/izoomframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

สร้างเฟรม Zoom ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง.

--------------------

> ```
> ตัวอย่างนี้แสดงการเพิ่มออบเจ็กต์ Zoom ไปที่ส่วนท้ายของคอลเลกชัน
>  (สมมติว่ามีสไลด์อย่างน้อยสองสไลด์ในงานนำเสนอ "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรม Zoom ใหม่หน่วยเป็นจุด |
| y | float | พิกัด y ของเฟรม Zoom ใหม่หน่วยเป็นจุด |
| width | float | ความกว้างของเฟรม Zoom ใหม่หน่วยเป็นจุด |
| height | float | ความสูงของเฟรม Zoom ใหม่หน่วยเป็นจุด |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) ที่อ้างอิงโดยเฟรม Zoom; ต้องเป็นของงานนำเสนอนี้ |
| image | [IPPImage](../../com.aspose.slides/ippimage) | ภาพสำหรับ [IPPImage](../../com.aspose.slides/ippimage) ที่อ้างอิงโดยสไลด์ |

**ผลลัพธ์:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - The newly created [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

สร้างเฟรม Zoom ใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งดัชนีที่ระบุ.

--------------------

> ```
> ตัวอย่างนี้แสดงการสร้างและแทรกออบเจ็กต์ Zoom ที่ตำแหน่งเฉพาะในคอลเลกชัน
>  (สมมติว่ามีสไลด์อย่างน้อยสองสไลด์ในงานนำเสนอ "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ซึ่งจะใส่เฟรม Zoom |
| x | float | พิกัด x ของเฟรม Zoom ใหม่หน่วยเป็นจุด |
| y | float | พิกัด y ของเฟรม Zoom ใหม่หน่วยเป็นจุด |
| width | float | ความกว้างของเฟรม Zoom ใหม่หน่วยเป็นจุด |
| height | float | ความสูงของเฟรม Zoom ใหม่หน่วยเป็นจุด |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) ที่อ้างอิงโดยเฟรม Zoom |

**ผลลัพธ์:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - The newly created [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

สร้างเฟรม Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งดัชนีที่ระบุ.

--------------------

> ```
> ตัวอย่างนี้แสดงการสร้างและแทรกออบเจ็กต์ Zoom ที่ตำแหน่งเฉพาะในคอลเลกชัน
>  (สมมติว่ามีสไลด์อย่างน้อยสองสไลด์ในงานนำเสนอ "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ซึ่งจะใส่เฟรม Zoom |
| x | float | พิกัด x ของเฟรม Zoom ใหม่หน่วยเป็นจุด |
| y | float | พิกัด y ของเฟรม Zoom ใหม่หน่วยเป็นจุด |
| width | float | ความกว้างของเฟรม Zoom ใหม่หน่วยเป็นจุด |
| height | float | ความสูงของเฟรม Zoom ใหม่หน่วยเป็นจุด |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) ที่อ้างอิงโดยเฟรม Zoom |
| image | [IPPImage](../../com.aspose.slides/ippimage) | ภาพสำหรับ [IPPImage](../../com.aspose.slides/ippimage) ที่อ้างอิงโดยสไลด์ |

**ผลลัพธ์:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - The newly created [IZoomFrame](../../com.aspose.slides/izoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

สร้างเฟรม Section Zoom ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง.

--------------------

> ```
> ตัวอย่างนี้แสดงการเพิ่มออบเจ็กต์ Section Zoom ไปที่ส่วนท้ายของคอลเลกชัน
>  (สมมติว่ามีส่วนอย่างน้อยสองส่วนในงานนำเสนอ "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรม Section Zoom ใหม่หน่วยเป็นจุด |
| y | float | พิกัด y ของเฟรม Section Zoom ใหม่หน่วยเป็นจุด |
| width | float | ความกว้างของเฟรม Section Zoom ใหม่หน่วยเป็นจุด |
| height | float | ความสูงของเฟรม Section Zoom ใหม่หน่วยเป็นจุด |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) ที่อ้างอิงโดยเฟรม Section Zoom; ต้องเป็นของงานนำเสนอนี้และต้องมีสไลด์อย่างน้อยหนึ่งสไลด์ |

**ผลลัพธ์:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - The newly created [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง.

--------------------

> ```
> ตัวอย่างนี้แสดงการเพิ่มออบเจ็กต์ Section Zoom ไปที่ส่วนท้ายของคอลเลกชัน
>  (สมมติว่ามีส่วนอย่างน้อยสองส่วนในงานนำเสนอ "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรม Section Zoom ใหม่หน่วยเป็นจุด |
| y | float | พิกัด y ของเฟรม Section Zoom ใหม่หน่วยเป็นจุด |
| width | float | ความกว้างของเฟรม Section Zoom ใหม่หน่วยเป็นจุด |
| height | float | ความสูงของเฟรม Section Zoom ใหม่หน่วยเป็นจุด |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) ที่อ้างอิงโดยเฟรม Section Zoom; ต้องเป็นของงานนำเสนอนี้และต้องมีสไลด์อย่างน้อยหนึ่งสไลด์ |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) ที่จะแสดงภายในเฟรม Section Zoom |

**ผลลัพธ์:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - The newly created [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

สร้างเฟรม Section Zoom ใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งดัชนีที่ระบุ.

--------------------

> ```
> ตัวอย่างนี้แสดงการสร้างและแทรกออบเจ็กต์ Section Zoom ที่ตำแหน่งเฉพาะในคอลเลกชัน
>  (สมมติว่ามีส่วนอย่างน้อยสองส่วนในงานนำเสนอ "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ซึ่งจะใส่เฟรม Section Zoom |
| x | float | พิกัด x ของเฟรม Section Zoom ใหม่หน่วยเป็นจุด |
| y | float | พิกัด y ของเฟรม Section Zoom ใหม่หน่วยเป็นจุด |
| width | float | ความกว้างของเฟรม Section Zoom ใหม่หน่วยเป็นจุด |
| height | float | ความสูงของเฟรม Section Zoom ใหม่หน่วยเป็นจุด |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) ที่อ้างอิงโดยเฟรม Section Zoom; ต้องเป็นของงานนำเสนอนี้และต้องมีสไลด์อย่างน้อยหนึ่งสไลด์ |

**ผลลัพธ์:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - The newly created [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งดัชนีที่ระบุ.

--------------------

> ```
> ตัวอย่างนี้แสดงการสร้างและแทรกออบเจ็กต์ Section Zoom ที่ตำแหน่งเฉพาะในคอลเลกชัน
>  (สมมติว่ามีส่วนอย่างน้อยสองส่วนในงานนำเสนอ "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ซึ่งจะใส่เฟรม Section Zoom |
| x | float | พิกัด x ของเฟรม Section Zoom ใหม่หน่วยเป็นจุด |
| y | float | พิกัด y ของเฟรม Section Zoom ใหม่หน่วยเป็นจุด |
| width | float | ความกว้างของเฟรม Section Zoom ใหม่หน่วยเป็นจุด |
| height | float | ความสูงของเฟรม Section Zoom ใหม่หน่วยเป็นจุด |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) ที่อ้างอิงโดยเฟรม Section Zoom; ต้องเป็นของงานนำเสนอนี้และต้องมีสไลด์อย่างน้อยหนึ่งสไลด์ |
| image | [IPPImage](../../com.aspose.slides/ippimage) | ภาพที่จะจัดแสดงภายในเฟรม Section Zoom |

**ผลลัพธ์:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - The newly created [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

สร้างเฟรม Summary Zoom ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง.

--------------------

> ```
> ตัวอย่างนี้แสดงการเพิ่มอ็อบเจ็กต์ Summary Zoom ไปที่ส่วนท้ายของคอลเลกชัน
>  (สมมติว่ามีส่วนอย่างน้อยสองส่วนในงานนำเสนอ "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรม Summary Zoom ใหม่หน่วยเป็นจุด |
| y | float | พิกัด y ของเฟรม Summary Zoom ใหม่หน่วยเป็นจุด |
| width | float | ความกว้างของเฟรม Summary Zoom ใหม่หน่วยเป็นจุด |
| height | float | ความสูงของเฟรม Summary Zoom ใหม่หน่วยเป็นจุด |

เมธอดนี้สร้าง Summary Zoom ใหม่และใส่คอลเลกชันของอ็อบเจ็กต์เข้าไปสำหรับทุกส่วนในงานนำเสนอนี้.

**ผลลัพธ์:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - The newly created [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

สร้างเฟรม Summary Zoom ใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งดัชนีที่ระบุ.

--------------------

> ```
> ตัวอย่างนี้แสดงการสร้างและแทรกอ็อบเจ็กต์ Summary Zoom ที่ตำแหน่งเฉพาะในคอลเลกชัน
>  (สมมติว่ามีส่วนอย่างน้อยสองส่วนในงานนำเสนอ "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ซึ่งจะใส่เฟรม Summary Zoom |
| x | float | พิกัด x ของเฟรม Summary Zoom ใหม่หน่วยเป็นจุด |
| y | float | พิกัด y ของเฟรม Summary Zoom ใหม่หน่วยเป็นจุด |
| width | float | ความกว้างของเฟรม Summary Zoom ใหม่หน่วยเป็นจุด |
| height | float | ความสูงของเฟรม Summary Zoom ใหม่หน่วยเป็นจุด |

เมธอดนี้สร้างเฟรม Summary Zoom ที่รวบรวมลิงก์สรุปสำหรับทุกส่วนในงานนำเสนอ.

**ผลลัพธ์:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - The newly created [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

สร้างเฟรมวัตถุ OLE ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง.

--------------------

> ```
> The following examples shows how to adding OLE Object Frames to Slides of PowerPoint Presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation ที่แทนไฟล์ PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // เข้าถึงสไลด์แรก
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // โหลดไฟล์ cel ไปยังสตรีม
>      FileInputStream fs = new FileInputStream("book1.xlsx");
>      ByteArrayOutputStream mstream = new ByteArrayOutputStream();
>      byte[] buf = new byte[4096];
> 
>      while (true)
>      {
>          int bytesRead = fs.read(buf, 0, buf.length);
>          if (bytesRead <= 0)
>              break;
>          mstream.write(buf, 0, bytesRead);
>      }
>      // สร้างอ็อบเจ็กต์ข้อมูลสำหรับการฝัง
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // เพิ่มรูปร่าง Ole Object Frame
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      //บันทึกไฟล์ PPTX ลงดิสก์
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรม OLE ใหม่หน่วยเป็นจุด |
| y | float | พิกัด y ของเฟรม OLE ใหม่หน่วยเป็นจุด |
| width | float | ความกว้างของเฟรม OLE ใหม่หน่วยเป็นจุด |
| height | float | ความสูงของเฟรม OLE ใหม่หน่วยเป็นจุด |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | ข้อมูลเกี่ยวกับข้อมูล OLE ที่ฝังอยู่ ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)) |

**ผลลัพธ์:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - The newly created [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

สร้างเฟรมวัตถุ OLE ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรม OLE ใหม่หน่วยเป็นจุด |
| y | float | พิกัด y ของเฟรม OLE ใหม่หน่วยเป็นจุด |
| width | float | ความกว้างของเฟรม OLE ใหม่หน่วยเป็นจุด |
| height | float | ความสูงของเฟรม OLE ใหม่หน่วยเป็นจุด |
| className | java.lang.String | ชื่อคลาสของวัตถุ OLE |
| path | java.lang.String | เส้นทางของไฟล์ที่เชื่อมโยง |

เส้นทางนี้ถูกจัดเก็บตามต้นฉบับในงานนำเสนอ หากระบุเส้นทางสัมพันธ์ ไฟล์จะไม่สามารถเข้าถึงได้เมื่อเปิดงานนำเสนอจากไดเรกทอรีอื่น.

**ผลลัพธ์:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - The newly created [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

สร้างเฟรมวัตถุ OLE ใหม่และแทรกเข้าไปในคอลเลกชันรูปร่างที่ตำแหน่งดัชนีที่ระบุ.

--------------------

> ```
> ตัวอย่างนี้แสดงการแทรกอ็อบเจ็กต์ OLE ที่ตำแหน่งอินเดกซ์ที่สอง:
>  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ซึ่งจะใส่เฟรมวัตถุ OLE |
| x | float | พิกัด x ของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | ข้อมูล OLE ที่ฝังอยู่ ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - ที่สร้างใหม่ [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และแทรกเข้าไปในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ.

**Parameters:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ใช้สำหรับแทรกเฟรมอ็อบเจ็กต์ OLE. |
| x | float | พิกัด x ของเฟรม OLEใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรม OLEใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรม OLEใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรม OLEใหม่, หน่วยเป็นจุด. |
| className | java.lang.String | ชื่อคลาสของอ็อบเจ็กต์ OLE. |
| path | java.lang.String | เส้นทางไปยังไฟล์ที่เชื่อมโยง.\n\nเส้นทางนี้จะถูกเก็บไว้โดยตรงในงานนำเสนอ หากระบุเส้นทางแบบสัมพันธ์ ไฟล์จะไม่สามารถเข้าถึงได้เมื่อเปิดงานนำเสนอจากไดเรกทอรีอื่น. |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - เฟรมอ็อบเจ็กต์ OLE ที่สร้างใหม่.
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

สร้างเฟรมวิดีโอใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปทรง.

**Parameters:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรมวิดีโอใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรมวิดีโอใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรมวิดีโอใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรมวิดีโอใหม่, หน่วยเป็นจุด. |
| fname | java.lang.String | เส้นทางหรือชื่อของไฟล์วิดีโอที่จะฝัง. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) ที่สร้างใหม่.
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

สร้างเฟรมวิดีโอใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปทรง.

**Parameters:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรมวิดีโอใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรมวิดีโอใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรมวิดีโอใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรมวิดีโอใหม่, หน่วยเป็นจุด. |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) ที่จะฝังในเฟรมวิดีโอ. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) ที่สร้างใหม่.
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

สร้างเฟรมวิดีโอใหม่และแทรกเข้าไปในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ.

**Parameters:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ใช้สำหรับแทรกเฟรมวิดีโอ. |
| x | float | พิกัด x ของเฟรมวิดีโอใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรมวิดีโอใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรมวิดีโอใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรมวิดีโอใหม่, หน่วยเป็นจุด. |
| fname | java.lang.String | เส้นทางหรือชื่อของไฟล์วิดีโอที่จะฝัง. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) ที่สร้างใหม่.
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับแทร็กซีดีและเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปทรง.

**Parameters:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นจุด. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) ที่สร้างใหม่.
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับแทร็กซีดีและแทรกเข้าไปในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ.

**Parameters:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ใช้สำหรับแทรกเฟรมเสียง. |
| x | float | พิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นจุด. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) ที่สร้างใหม่.
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับไฟล์เสียงภายนอกและเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปทรง.

**Parameters:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| fname | java.lang.String | เส้นทางหรือชื่อของไฟล์เสียงภายนอกที่จะเชื่อมโยง. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) ที่สร้างใหม่.
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับไฟล์เสียงภายนอกและแทรกเข้าไปในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ.

**Parameters:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ใช้สำหรับแทรกเฟรมเสียง. |
| x | float | พิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| fname | java.lang.String | เส้นทางหรือชื่อของไฟล์เสียงภายนอกที่จะเชื่อมโยง. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) ที่สร้างใหม่.
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

สร้างเฟรมเสียงใหม่พร้อมไฟล์ WAV ที่ฝังอยู่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปทรง เสียงที่ฝังอยู่จะถูกเพิ่มไปยังคอลเลกชัน Presentation.Audios.

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีสร้าง Audio Frame.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation ที่แทนไฟล์งานนำเสนอ
>  Presentation pres = new Presentation();
>  try {
>      // ดึงสไลด์แรก
>      ISlide sld = pres.getSlides().get_Item(0);
>      // โหลดไฟล์เสียง wav ไปยังสตรีม
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // เพิ่ม Audio Frame
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // ตั้งค่าโหมดการเล่นและระดับเสียงของ Audio
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // เขียนไฟล์ PowerPoint ลงดิสก์
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| audio_stream | java.io.InputStream | สตรีมอินพุตที่มีข้อมูลเสียง WAV เพื่อฝัง. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) ที่สร้างใหม่.
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

สร้างเฟรมเสียงใหม่พร้อมไฟล์ WAV ที่ฝังอยู่และแทรกเข้าไปในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ เสียงที่ฝังอยู่จะถูกเพิ่มไปยังคอลเลกชัน Presentation.Audios.

**Parameters:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ใช้สำหรับแทรกเฟรมเสียง. |
| x | float | พิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| audio_stream | java.io.InputStream | สตรีมอินพุตที่มีข้อมูลเสียง WAV เพื่อฝัง. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) ที่สร้างใหม่.
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

สร้างเฟรมเสียงใหม่และเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปทรงโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios.

**Parameters:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | [IAudio](../../com.aspose.slides/iaudio) อินสแตนซ์จากคอลเลกชัน Presentation.Audios. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) ที่สร้างใหม่.
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

สร้างเฟรมเสียงใหม่และแทรกเข้าไปในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios.

**Parameters:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ใช้สำหรับแทรกเฟรมเสียง. |
| x | float | พิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นจุด. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | อินสแตนซ์ [IAudio](../../com.aspose.slides/iaudio) จากคอลเลกชัน Presentation.Audios เพื่อฝัง. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) ที่สร้างใหม่.
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

ส่งคืนดัชนีเริ่มจากศูนย์ของการพบครั้งแรกของรูปร่างที่ระบุในคอลเลกชันรูปทรง หากไม่พบ มิฉะนั้น \\u20131.

**Parameters:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | รูปร่างที่ต้องการค้นหาในคอลเลกชัน. |

**Returns:**
int - ดัชนีเริ่มจากศูนย์ของการพบครั้งแรกของรูปร่างในคอลเลกชันรูปทรง หากไม่พบ, มิฉะนั้น \\u20131.
### toArray() {#toArray--}
```
public final IShape[] toArray()
```

สร้างและส่งกลับอาร์เรย์ที่มีรูปร่างทั้งหมด.

**Returns:**
com.aspose.slides.IShape[] - อาร์เรย์ของอ็อบเจ็กต์ [IShape](../../com.aspose.slides/ishape).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

สร้างและส่งกลับอาร์เรย์ที่มีรูปร่างทั้งหมดในช่วงที่ระบุ.

**Parameters:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| startIndex | int | ดัชนีของรูปร่างแรกที่ต้องการส่งกลับ. |
| count | int | จำนวนรูปร่างที่ต้องการส่งกลับ. |

**Returns:**
com.aspose.slides.IShape[] - อาร์เรย์ของอ็อบเจ็กต์ [IShape](../../com.aspose.slides/ishape).
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

ย้ายรูปร่างที่ระบุไปยังตำแหน่งใหม่ภายในคอลเลกชันรูปทรง.

**Parameters:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| index | int | ดัชนีเป้าหมายเริ่มจากศูนย์ที่รูปร่างจะถูกวาง. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) ที่จะย้ายภายในคอลเลกชัน. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

ย้ายรูปร่างที่ระบุหลายตัวภายในคอลเลกชันรูปทรง โดยเริ่มวางจากดัชนีที่กำหนด; รูปร่างต่อไปจะวางตามลำดับที่ให้ไว้.
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | หนึ่งหรือหลายอินสแตนซ์ของ [IShape](../../com.aspose.slides/ishape) เพื่อย้ายภายในคอลเลกชัน. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

สร้างอัตโนมัติ shape ใหม่ด้วยการจัดรูปแบบค่าเริ่มต้นและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน shape.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) ของ shape อัตโนมัติที่จะเพิ่ม. |
| x | float | พิกัด x ของกรอบ shape, หน่วยเป็นจุด. |
| y | float | พิกัด y ของกรอบ shape, หน่วยเป็นจุด. |
| width | float | ความกว้างของกรอบ shape, หน่วยเป็นจุด. |
| height | float | ความสูงของกรอบ shape, หน่วยเป็นจุด. |

**ส่งคืน:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) ที่สร้างใหม่.

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

สร้างอัตโนมัติ shape ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน shape โดยอาจกำหนดรูปแบบเทมเพลตค่าเริ่มต้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) ของ shape อัตโนมัติที่จะเพิ่ม. |
| x | float | พิกัด x ของกรอบ shape, หน่วยเป็นจุด. |
| y | float | พิกัด y ของกรอบ shape, หน่วยเป็นจุด. |
| width | float | ความกว้างของกรอบ shape, หน่วยเป็นจุด. |
| height | float | ความสูงของกรอบ shape, หน่วยเป็นจุด. |
| createFromTemplate | boolean | true เพื่อใช้สไตล์เทมเพลตค่าเริ่มต้น (สไตล์ง่าย, ข้อความกึ่งกลาง, และชื่อไม่ว่าง) กับ shape ใหม่; false เพื่อสร้าง shape โดยตั้งค่าทุกคุณสมบัติเป็นค่าเริ่มต้นของมัน. |

**ส่งคืน:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) ที่สร้างใหม่.

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

สร้างสี่เหลี่ยมอัตโนมัติใหม่เพื่อโฮสต์เนื้อหาทางคณิตศาสตร์และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน shape.

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มสมการคณิตศาสตร์ใน PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape mathShape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 720, 150);
>      IMathParagraph mathParagraph = ((MathPortion)mathShape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>      IMathFraction fraction = new MathematicalText("x").divide("y");
>      mathParagraph.add(new MathBlock(fraction));
>      IMathBlock mathBlock = new MathematicalText("c")
>          .setSuperscript("2")
>          .join("=")
>          .join(new MathematicalText("a").setSuperscript("2"))
>          .join("+")
>          .join(new MathematicalText("b").setSuperscript("2"));
>      mathParagraph.add(mathBlock);
>      pres.save("math.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด x ของกรอบ shape, หน่วยเป็นจุด. |
| y | float | พิกัด y ของกรอบ shape, หน่วยเป็นจุด. |
| width | float | ความกว้างของกรอบ shape, หน่วยเป็นจุด. |
| height | float | ความสูงของกรอบ shape, หน่วยเป็นจุด. |

**ส่งคืน:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) ที่สร้างใหม่.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

สร้างอัตโนมัติ shape ใหม่และแทรกลงในคอลเลกชัน shape ที่ตำแหน่งที่ระบุ พร้อมใช้สไตล์เทมเพลตค่าเริ่มต้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ต้องการแทรก shape อัตโนมัติใหม่. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) ของ shape อัตโนมัติที่จะใส่. |
| x | float | พิกัด x ของกรอบ shape, หน่วยเป็นจุด. |
| y | float | พิกัด y ของกรอบ shape, หน่วยเป็นจุด. |
| width | float | ความกว้างของกรอบ shape, หน่วยเป็นจุด. |
| height | float | ความสูงของกรอบ shape, หน่วยเป็นจุด. |

**ส่งคืน:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) ที่สร้างใหม่.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

สร้างอัตโนมัติ shape ใหม่และแทรกลงในคอลเลกชัน shape ที่ตำแหน่งที่ระบุ โดยอาจกำหนดสไตล์เทมเพลตค่าเริ่มต้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ต้องการแทรก shape อัตโนมัติ. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) ของ shape อัตโนมัติที่จะใส่. |
| x | float | พิกัด x ของกรอบ shape, หน่วยเป็นจุด. |
| y | float | พิกัด y ของกรอบ shape, หน่วยเป็นจุด. |
| width | float | ความกว้างของกรอบ shape, หน่วยเป็นจุด. |
| height | float | ความสูงของกรอบ shape, หน่วยเป็นจุด. |
| createFromTemplate | boolean | true เพื่อใช้สไตล์เทมเพลตค่าเริ่มต้น (รวมชื่อไม่ว่าง, สไตล์ง่าย, ข้อความกึ่งกลาง); false เพื่อสร้าง shape ด้วยคุณสมบัติทั้งหมดเป็นค่าเริ่มต้น. |

**ส่งคืน:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) ที่สร้างใหม่.

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

สร้างกลุ่ม shape ว่างใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน shape กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดีกับ shape ที่เพิ่มเข้ามา

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มกลุ่มรูปร่างลงในสไลด์ของ PowerPoint Presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation
>  Presentation pres = new Presentation();
>  try {
>      // ดึงสไลด์แรก
>      ISlide sld = pres.getSlides().get_Item(0);
>      // เข้าถึงคอลเลกชันรูปร่างของสไลด์
>      IShapeCollection slideShapes = sld.getShapes();
>      // เพิ่มกลุ่มรูปร่างลงในสไลด์
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // เพิ่มรูปร่างภายในกลุ่มรูปร่างที่เพิ่มไว้
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // เพิ่มเฟรมของกลุ่มรูปร่าง
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // เขียนไฟล์ PPTX ลงดิสก์
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**ส่งคืน:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) ที่สร้างใหม่.

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

สร้างกลุ่ม shape ใหม่, แปลงภาพ SVG ที่ระบุเป็น shape แต่ละรูป, และเพิ่มกลุ่มที่ได้ลงในตำแหน่งสุดท้ายของคอลเลกชัน shape

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) ที่มีเนื้อหาเวก터เพื่อแปลงเป็น shape. |
| x | float | พิกัด x ของกรอบกลุ่ม, หน่วยเป็นจุด. |
| y | float | พิกัด y ของกรอบกลุ่ม, หน่วยเป็นจุด. |
| width | float | ความกว้างของกรอบกลุ่ม, หน่วยเป็นจุด. |
| height | float | ความสูงของกรอบกลุ่ม, หน่วยเป็นจุด. |

**ส่งคืน:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) ที่สร้างใหม่.

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

สร้างกลุ่ม shape ว่างใหม่และแทรกลงในคอลเลกชัน shape ที่ตำแหน่งที่ระบุ กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดีกับ shape ที่เพิ่มเข้ามา

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ต้องการแทรกกลุ่ม shape. |

**ส่งคืน:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) ที่สร้างใหม่.

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

สร้าง connector shape ใหม่ด้วยสไตล์เทมเพลตค่าเริ่มต้นและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน shape

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มตัวเชื่อม (ตัวเชื่อมแบบโค้ง) ระหว่างสองรูปร่าง (วงรีและสี่เหลี่ยม) ใน PowerPoint Presentation.
>  
  
>  // สร้างอินสแตนซ์ของคลาส Presentation ที่แทนไฟล์ PPTX
>  Presentation pres = new Presentation();
>  try {
>      // เข้าถึงคอลเลกชันรูปร่างของสไลด์เฉพาะ
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // เพิ่มรูปร่างอัตโนมัติแบบวงรี
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // เพิ่มรูปร่างอัตโนมัติแบบสี่เหลี่ยม
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // เพิ่มรูปร่างตัวเชื่อมลงในคอลเลกชันรูปร่างของสไลด์
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // เชื่อมต่อรูปร่างโดยใช้ตัวเชื่อม
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // เรียกใช้ reroute ที่กำหนดเส้นทางสั้นที่สุดโดยอัตโนมัติระหว่างรูปร่าง
>      connector.reroute();
>      // บันทึกงานนำเสนอ
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) ของ connector shape ที่ต้องการเพิ่ม. |
| x | float | พิกัด x ของกรอบ connector, หน่วยเป็นจุด. |
| y | float | พิกัด y ของกรอบ connector, หน่วยเป็นจุด. |
| width | float | ความกว้างของกรอบ connector, หน่วยเป็นจุด. |
| height | float | ความสูงของกรอบ connector, หน่วยเป็นจุด. |

**ส่งคืน:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) ที่สร้างใหม่.

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

สร้าง connector shape ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน shape โดยอาจใช้สไตล์เทมเพลตค่าเริ่มต้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) ของ connector shape ที่จะสร้าง. |
| x | float | พิกัด x ของกรอบ connector, หน่วยเป็นจุด. |
| y | float | พิกัด y ของกรอบ connector, หน่วยเป็นจุด. |
| width | float | ความกว้างของกรอบ connector, หน่วยเป็นจุด. |
| height | float | ความสูงของกรอบ connector, หน่วยเป็นจุด. |
| createFromTemplate | boolean | true เพื่อใช้สไตล์เทมเพลตค่าเริ่มต้น (ชื่อไม่ว่าง, สไตล์ง่าย); false เพื่อสร้าง connector ด้วยค่าคุณสมบัติเริ่มต้น. |

**ส่งคืน:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) ที่สร้างใหม่.

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

สร้าง connector shape ใหม่และแทรกลงในคอลเลกชัน shape ที่ตำแหน่งที่ระบุ โดยใช้สไตล์เทมเพลตค่าเริ่มต้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ต้องการแทรก connector shape. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) ของ connector shape ที่จะใส่. |
| x | float | พิกัด x ของกรอบ connector, หน่วยเป็นจุด. |
| y | float | พิกัด y ของกรอบ connector, หน่วยเป็นจุด. |
| width | float | ความกว้างของกรอบ connector, หน่วยเป็นจุด. |
| height | float | ความสูงของกรอบ connector, หน่วยเป็นจุด. |

**ส่งคืน:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) ที่สร้างใหม่.

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

สร้าง connector shape ใหม่และแทรกลงในคอลเลกชัน shape ที่ตำแหน่งที่ระบุ โดยอาจใช้สไตล์เทมเพลตค่าเริ่มต้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ต้องการแทรก connector shape. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) ของ connector shape ที่จะใส่. |
| x | float | พิกัด x ของกรอบ connector, หน่วยเป็นจุด. |
| y | float | พิกัด y ของกรอบ connector, หน่วยเป็นจุด. |
| width | float | ความกว้างของกรอบ connector, หน่วยเป็นจุด. |
| height | float | ความสูงของกรอบ connector, หน่วยเป็นจุด. |
| createFromTemplate | boolean | true เพื่อใช้สไตล์เทมเพลตค่าเริ่มต้น (ชื่อไม่ว่าง, สไตล์ง่าย); false เพื่อสร้าง connector ด้วยค่าคุณสมบัติเริ่มต้น. |

**ส่งคืน:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) ที่สร้างใหม่.

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

สร้าง picture frame ใหม่ที่บรรจุภาพที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน shape

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeType | int | กำหนดประเภท shape ที่อยู่ใน [ShapeType](../../com.aspose.slides/shapetype) ยกเว้นรูปแบบเส้นทั้งหมด: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | พิกัด x ของ picture frame, หน่วยเป็นจุด. |
| y | float | พิกัด y ของ picture frame, หน่วยเป็นจุด. |
| width | float | ความกว้างของ picture frame, หน่วยเป็นจุด. |
| height | float | ความสูงของ picture frame, หน่วยเป็นจุด. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) ที่จะแสดงใน picture frame. |

**ส่งคืน:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) ที่สร้างใหม่.

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

สร้าง picture frame ใหม่ที่บรรจุภาพที่ระบุและแทรกลงในคอลเลกชัน shape ที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ต้องการแทรก picture frame. |
| shapeType | int | กำหนดประเภท shape ที่อยู่ใน [ShapeType](../../com.aspose.slides/shapetype) ยกเว้นรูปแบบเส้นทั้งหมด: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | พิกัด x ของ picture frame, หน่วยเป็นจุด. |
| y | float | พิกัด y ของ picture frame, หน่วยเป็นจุด. |
| width | float | ความกว้างของ picture frame, หน่วยเป็นจุด. |
| height | float | ความสูงของ picture frame, หน่วยเป็นจุด. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) ที่จะแสดงใน picture frame. |

**ส่งคืน:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) ที่สร้างใหม่.

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

สร้างตารางใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน shape

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มตารางใน PowerPoint Presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation ที่แทนไฟล์ PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // เข้าถึงสไลด์แรก
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // กำหนดคอลัมน์พร้อมความกว้างและแถวพร้อมความสูง
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // เพิ่มรูปร่างตารางลงในสไลด์
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // ตั้งค่ารูปแบบเส้นขอบสำหรับแต่ละเซลล์
>      for (int row = 0; row < tbl.getRows().size(); row++)
>      {
>          for (int cell = 0; cell < tbl.getRows().get_Item(row).size(); cell++)
>          {
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().setFillType((FillType.Solid));
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().setWidth(5);
>          }
>      }
>      // รวมเซลล์ที่ 1 และ 2 ของแถวที่ 1
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // เพิ่มข้อความลงในเซลล์ที่รวมแล้ว
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // บันทึกไฟล์ PPTX ลงดิสก์
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด x ของตาราง, หน่วยเป็น points. |
| y | float | พิกัด y ของตาราง, หน่วยเป็น points. |
| columnWidths | double[] | อาเรย์ของ double ที่แสดงความกว้างของคอลัมน์ของตาราง, หน่วยเป็น points. |
| rowHeights | double[] | อาเรย์ของ double ที่แสดงความสูงของแถวของตาราง, หน่วยเป็น points. |

**ค่าที่ส่งคืน:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) ที่สร้างขึ้นใหม่.

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

สร้างตารางใหม่และแทรกลงในคอลเลกชันรูปทรงตามตำแหน่งที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นศูนย์ที่ต้องการแทรกตาราง. |
| x | float | พิกัด x ของตาราง, หน่วยเป็น points. |
| y | float | พิกัด y ของตาราง, หน่วยเป็น points. |
| columnWidths | double[] | อาเรย์ของ double ที่แสดงความกว้างของคอลัมน์ของตาราง, หน่วยเป็น points. |
| rowHeights | double[] | อาเรย์ของ double ที่แสดงความสูงของแถวของตาราง, หน่วยเป็น points. |

**ค่าที่ส่งคืน:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) ที่สร้างขึ้นใหม่.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบรูปทรงที่ตำแหน่งที่ระบุจากคอลเลกชันรูปทรง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นศูนย์ของรูปทรงที่ต้องการลบ. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

ลบการเกิดครั้งแรกของรูปทรงที่ระบุจากคอลเลกชันรูปทรง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) ที่จะลบ. |

### clear() {#clear--}
```
public final void clear()
```

ลบรูปทรงทั้งหมดจากคอลเลกชันรูปทรง

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

คืนค่า enumerator ที่ทำการวนซ้ำผ่านคอลเลกชัน

**ค่าที่ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**ค่าที่ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - An java.util.Iterator for the entire collection.

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

รับอ็อบเจกต์รูปทรงกลุ่มแม่สำหรับคอลเลกชันรูปทรง. อ่านอย่างเดียว [IGroupShape](../../com.aspose.slides/igroupshape).

**ค่าที่ส่งคืน:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

สร้างสำเนาของรูปทรงที่ระบุและเพิ่มไปยังท้ายคอลเลกชันรูปทรง

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | รูปร่างที่จะคัดลอก. |
| x | float | พิกัด x ของกรอบรูปทรงใหม่, หน่วยเป็น points. |
| y | float | พิกัด y ของกรอบรูปทรงใหม่, หน่วยเป็น points. |
| width | float | ความกว้างของกรอบรูปทรงใหม่, หน่วยเป็น points. |
| height | float | ความสูงของกรอบรูปทรงใหม่, หน่วยเป็น points. |

**ค่าที่ส่งคืน:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) ที่สร้างขึ้นใหม่.

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

สร้างสำเนาของรูปทรงที่ระบุและเพิ่มไปยังท้ายคอลเลกชันรูปทรง. รูปทรงใหม่จะคงความกว้างและความสูงของ sourceShape .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | รูปร่างที่จะคัดลอก. |
| x | float | พิกัด x ของกรอบรูปทรงใหม่, หน่วยเป็น points. |
| y | float | พิกัด y ของกรอบรูปทรงใหม่, หน่วยเป็น points. |

**ค่าที่ส่งคืน:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) ที่สร้างขึ้นใหม่.

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

สร้างสำเนาของรูปทรงที่ระบุและเพิ่มไปยังท้ายคอลเลกชันรูปทรง. รูปทรงที่คัดลอกจะคงตำแหน่งและขนาดของต้นฉบับ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) ที่จะคัดลอก. |

**ค่าที่ส่งคืน:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) ที่สร้างขึ้นใหม่.

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

สร้างสำเนาของรูปทรงที่ระบุและแทรกลงในคอลเลกชันรูปทรงตามตำแหน่งที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นศูนย์ที่ต้องการแทรกรูปทรงที่คัดลอก. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) ที่จะคัดลอก. |
| x | float | พิกัด x ของกรอบรูปทรงที่คัดลอก, หน่วยเป็น points. |
| y | float | พิกัด y ของกรอบรูปทรงที่คัดลอก, หน่วยเป็น points. |
| width | float | ความกว้างของกรอบรูปทรงที่คัดลอก, หน่วยเป็น points. |
| height | float | ความสูงของกรอบรูปทรงที่คัดลอก, หน่วยเป็น points. |

**ค่าที่ส่งคืน:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) ที่สร้างขึ้นใหม่.

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

สร้างสำเนาของรูปทรงที่ระบุและแทรกลงในคอลเลกชันรูปทรงตามตำแหน่งที่ระบุ. รูปทรงใหม่จะคงความกว้างและความสูงของ sourceShape .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นศูนย์ที่ต้องการแทรกรูปทรงที่คัดลอก. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) ที่จะคัดลอก. |
| x | float | พิกัด x ของกรอบรูปทรงที่คัดลอก, หน่วยเป็น points. |
| y | float | พิกัด y ของกรอบรูปทรงที่คัดลอก, หน่วยเป็น points. |

**ค่าที่ส่งคืน:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) ที่สร้างขึ้นใหม่.

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

สร้างสำเนาของรูปทรงที่ระบุและแทรกลงในคอลเลกชันรูปทรงตามตำแหน่งที่ระบุ. รูปทรงที่คัดลอกจะคงตำแหน่งและขนาดของต้นฉบับ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นศูนย์ที่ต้องการแทรกรูปทรงที่คัดลอก. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) ที่จะคัดลอก. |

**ค่าที่ส่งคืน:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) ที่สร้างขึ้นใหม่.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย. |
| index | int | ดัชนีเริ่มต้นในอาเรย์เป้าหมาย. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันนั้นทำงานแบบ synchronized (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean .

**ค่าที่ส่งคืน:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่ารากของการซิงโครไนซ์. อ่านอย่างเดียว Object .

**ค่าที่ส่งคืน:**
java.lang.Object