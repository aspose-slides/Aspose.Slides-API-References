---
title: IShapeCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของคอลเลกชันของรูปร่าง.
type: docs
url: /th/com.aspose.slides/ishapecollection/
---
**อินเทอร์เฟซที่ดำเนินการทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

แสดงถึงคอลเลกชันของรูปร่าง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงอิลเมนต์ที่ตำแหน่งที่ระบุ |
| [getParentGroup()](#getParentGroup--) | ดึงอ็อบเจ็กต์รูปแบบกลุ่มแม่สำหรับคอลเลกชันของรูปร่าง |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | สร้างไดอะแกรม SmartArt และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | สร้างเฟรม Zoom ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | สร้างเฟรม Zoom ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | สร้างเฟรม Zoom ใหม่และแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | สร้างเฟรม Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | สร้างเฟรม Section Zoom ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | สร้างเฟรม Section Zoom ใหม่และแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | สร้างเฟรม Summary Zoom ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | สร้างเฟรม Summary Zoom ใหม่และแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | สร้างเฟรมวิดีโอใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | สร้างเฟรมวิดีโอใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | สร้างเฟรมวิดีโอใหม่และแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | สร้างเฟรมออดิโอใหม่ที่เชื่อมโยงกับแทร็ก CD และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | สร้างเฟรมออดิโอใหม่ที่เชื่อมโยงกับแทร็ก CD และแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | สร้างเฟรมออดิโอใหม่ที่เชื่อมโยงกับไฟล์ออดิโอภายนอกและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | สร้างเฟรมออดิโอใหม่ที่เชื่อมโยงกับไฟล์ออดิโอภายนอกและแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | สร้างเฟรมออดิโอใหม่พร้อมไฟล์ WAV ที่ฝังอยู่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | สร้างเฟรมออดิโอใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่างโดยใช้อ็อบเจ็กต์ออดิโอที่มีอยู่จากรายการ Presentation.Audios |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | สร้างเฟรมออดิโอใหม่พร้อมไฟล์ WAV ที่ฝังอยู่และแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | สร้างเฟรมออดิโอใหม่และแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุโดยใช้อ็อบเจ็กต์ออดิโอที่มีอยู่จากรายการ Presentation.Audios |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | คืนค่าอินเด็กซ์ที่เริ่มจากศูนย์ของการปรากฏครั้งแรกของรูปร่างที่ระบุในคอลเลกชัน |
| [toArray()](#toArray--) | สร้างและคืนค่าอาเรย์ที่มีรูปร่างทั้งหมด |
| [toArray(int startIndex, int count)](#toArray-int-int-) | สร้างและคืนค่าอาเรย์ที่มีรูปร่างทั้งหมดในช่วงที่ระบุ |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | ย้ายรูปร่างที่ระบุไปยังตำแหน่งใหม่ในคอลเลกชันรูปร่าง |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Moves the specified shapes within the shape collection, placing them starting at the given index. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | สร้างรูปร่างอัตโนมัติใหม่ด้วยการจัดรูปแบบค่าเริ่มต้นและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | สร้างรูปร่างอัตโนมัติใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง, โดยอาจเริ่มต้นด้วยการจัดรูปแบบเทมเพลตค่าเริ่มต้น |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | สร้างรูปสี่เหลี่ยมอัตโนมัติใหม่เพื่อเก็บเนื้อหาคณิตศาสตร์และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | สร้างรูปร่างอัตโนมัติใหม่และแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุด้วยการจัดรูปแบบเทมเพลตค่าเริ่มต้น |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | สร้างรูปร่างอัตโนมัติใหม่และแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ, โดยอาจเริ่มต้นด้วยการจัดสไตล์เทมเพลตค่าเริ่มต้น |
| [addGroupShape()](#addGroupShape--) | สร้างกลุ่มรูปร่างเปล่าใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | สร้างกลุ่มรูปร่างใหม่, แปลงภาพ SVG ที่ระบุเป็นรูปร่างย่อยและเพิ่มกลุ่มที่ได้ไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [insertGroupShape(int index)](#insertGroupShape-int-) | สร้างกลุ่มรูปร่างเปล่าใหม่และแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | สร้างรูปเชื่อมต่อใหม่ด้วยสไตล์เทมเพลตค่าเริ่มต้นและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | สร้างรูปเชื่อมต่อใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง, โดยอาจใช้สไตล์เทมเพลตค่าเริ่มต้น |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | สร้างรูปเชื่อมต่อใหม่และแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุด้วยสไตล์เทมเพลตค่าเริ่มต้น |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | สร้างรูปเชื่อมต่อใหม่และแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ, โดยอาจใช้สไตล์เทมเพลตค่าเริ่มต้น |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | สร้างเฟรมรูปภาพใหม่ที่บรรจุภาพที่ระบุและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | สร้างเฟรมรูปภาพใหม่ที่บรรจุภาพที่ระบุและแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Creates a new table and adds it to the end of the shape collection. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Creates a new table and inserts it into the shape collection at the specified index. |
| [removeAt(int index)](#removeAt-int-) | ลบรูปร่างที่ตำแหน่งที่ระบุออกจากคอลเลกชันรูปร่าง |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | ลบการปรากฏครั้งแรกของรูปร่างที่ระบุออกจากคอลเลกชันรูปร่าง |
| [clear()](#clear--) | ลบรูปร่างทั้งหมดออกจากคอลเลกชันรูปร่าง |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | สร้างสำเนาของรูปร่างที่ระบุและแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | สร้างสำเนาของรูปร่างที่ระบุและแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | สร้างสำเนาของรูปร่างที่ระบุและแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

ดึงอิลเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IShape](../../com.aspose.slides/ishape).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

ดึงอ็อบเจ็กต์รูปแบบกลุ่มแม่สำหรับคอลเลกชันของรูปร่าง. อ่านอย่างเดียว [IGroupShape](../../com.aspose.slides/igroupshape).

**คืนค่า:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| type | int | ประเภทของแผนภูมิที่ต้องการเพิ่ม |
| x | float | พิกัด x ของแผนภูมิใหม่, หน่วยเป็นจุด |
| y | float | พิกัด y ของแผนภูมิใหม่, หน่วยเป็นจุด |
| width | float | ความกว้างของแผนภูมิ, หน่วยเป็นจุด |
| height | float | ความสูงของแผนภูมิ, หน่วยเป็นจุด |

**คืนค่า:**
[IChart](../../com.aspose.slides/ichart) - ที่สร้างขึ้นใหม่ [IChart](../../com.aspose.slides/ichart)

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| type | int | ประเภทของแผนภูมิที่ต้องการเพิ่ม |
| x | float | พิกัด x ของแผนภูมิใหม่, หน่วยเป็นจุด |
| y | float | พิกัด y ของแผนภูมิใหม่, หน่วยเป็นจุด |
| width | float | ความกว้างของแผนภูมิ, หน่วยเป็นจุด |
| height | float | ความสูงของแผนภูมิ, หน่วยเป็นจุด |
| initWithSample | boolean | true เพื่อเริ่มต้นแผนภูมิใหม่ด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า; false เพื่อสร้างแผนภูมิโดยไม่มีซีรีส์และมีการตั้งค่าน้อยที่สุดซึ่งทำให้การสร้างเร็วขึ้น |

**คืนค่า:**
[IChart](../../com.aspose.slides/ichart) - ที่สร้างขึ้นใหม่ [IChart](../../com.aspose.slides/ichart)

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

สร้างไดอะแกรม SmartArt และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรมไดอะแกรม, หน่วยเป็นจุด |
| y | float | พิกัด y ของเฟรมไดอะแกรม, หน่วยเป็นจุด |
| width | float | ความกว้างของเฟรมไดอะแกรม, หน่วยเป็นจุด |
| height | float | ความสูงของเฟรมไดอะแกรม, หน่วยเป็นจุด |
| layoutType | int | ประเภทการจัดวางของ SmartArt |

**คืนค่า:**
[ISmartArt](../../com.aspose.slides/ismartart) - ที่สร้างขึ้นใหม่ [ISmartArt](../../com.aspose.slides/ismartart)

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| type | int | ประเภทของแผนภูมิที่ต้องการสร้าง |
| x | float | พิกัด x ของแผนภูมิใหม่, หน่วยเป็นจุด |
| y | float | พิกัด y ของแผนภูมิใหม่, หน่วยเป็นจุด |
| width | float | ความกว้างของแผนภูมิใหม่, หน่วยเป็นจุด |
| height | float | ความสูงของแผนภูมิใหม่, หน่วยเป็นจุด |
| index | int | อินเด็กซ์ที่เริ่มจากศูนย์ซึ่งตำแหน่งที่จะแทรกแผนภูมิใหม่ในคอลเลกชันรูปร่าง |

**คืนค่า:**
[IChart](../../com.aspose.slides/ichart) - ที่สร้างขึ้นใหม่ [IChart](../../com.aspose.slides/ichart)

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วแทรกเข้าคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| type | int | ประเภทของแผนภูมิที่ต้องการสร้าง |
| x | float | พิกัด x ของแผนภูมิใหม่, หน่วยเป็นจุด |
| y | float | พิกัด yของแผนภูมิใหม่, หน่วยเป็นจุด |
| width | float | ความกว้างของแผนภูมิใหม่, หน่วยเป็นจุด |
| height | float | ความสูงของแผนภูมิใหม่, หน่วยเป็นจุด |
| index | int | อินเด็กซ์ที่เริ่มจากศูนย์ซึ่งตำแหน่งที่จะแทรกแผนภูมิใหม่ในคอลเลกชันรูปร่าง |
| initWithSample | boolean | true เพื่อเริ่มต้นแผนภูมิใหม่ด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า; false เพื่อสร้างแผนภูมิโดยไม่มีซีรีส์และมีการตั้งค่าน้อยที่สุดซึ่งทำให้การสร้างเร็วขึ้น |
| initWithSample | boolean | True เพื่อเริ่มต้นแผนภูมิใหม่ด้วยข้อมูลและการตั้งค่าชุดตัวอย่าง; false เพื่อสร้างแผนภูมิที่ไม่มีชุดข้อมูลและมีการตั้งค่าขั้นต่ำ ซึ่งทำให้การสร้างเร็วขึ้น. |

**คืนค่า:**
[IChart](../../com.aspose.slides/ichart) - The newly created [IChart](../../com.aspose.slides/ichart).
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | ข้อมูล OLE ที่ฝังอยู่ ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**คืนค่า:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - The newly created [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| className | java.lang.String | ชื่อคลาสของอ็อบเจ็กต์ OLE. |
| path | java.lang.String | เส้นทางไปยังไฟล์ที่เชื่อมโยง.  

เส้นทางนี้จะถูกจัดเก็บตามต้นฉบับในงานนำเสนอ หากระบุเป็นเส้นทางสัมพันธ์ ไฟล์จะไม่สามารถเข้าถึงได้เมื่อเปิดงานนำเสนอจากไดเรกทอรีอื่น. |

**คืนค่า:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - The newly created [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และแทรกเข้าไปในคอลเลกชันรูปทรงตามตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีศูนย์ฐานที่ต้องการแทรกเฟรม OLE. |
| x | float | พิกัด x ของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | ข้อมูล OLE ที่ฝังอยู่ ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**คืนค่า:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - The newly created [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และแทรกเข้าไปในคอลเลกชันรูปทรงตามตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีศูนย์ฐานที่ต้องการแทรกเฟรม OLE. |
| x | float | พิกัด x ของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรม OLE ใหม่, หน่วยเป็นจุด. |
| className | java.lang.String | ชื่อคลาสของอ็อบเจ็กต์ OLE. |
| path | java.lang.String | เส้นทางไปยังไฟล์ที่เชื่อมโยง.  

เส้นทางนี้จะถูกจัดเก็บตามต้นฉบับในงานนำเสนอ หากระบุเป็นเส้นทางสัมพันธ์ ไฟล์จะไม่สามารถเข้าถึงได้เมื่อเปิดงานนำเสนอจากไดเรกทอรีอื่น. |

**คืนค่า:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - The newly created [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

สร้างเฟรม Zoom ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง

--------------------

> ```
> ตัวอย่างนี้แสดงการเพิ่มออบเจกต์ Zoom ไปที่ส่วนท้ายของคอลเลกชัน
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรม Zoom ใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรม Zoom ใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรม Zoom ใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรม Zoom ใหม่, หน่วยเป็นจุด. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) ที่อ้างอิงโดยเฟรม Zoom; ต้องเป็นของงานนำเสนอเดียวกันนี้. |

**คืนค่า:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - The newly created [IZoomFrame](../../com.aspose.slides/izoomframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

สร้างเฟรม Zoom ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง

--------------------

> ```
> ตัวอย่างนี้แสดงการเพิ่มออบเจกต์ Zoom ไปที่ส่วนท้ายของคอลเลกชัน
> (สมมติว่ามีสไลด์อย่างน้อยสองสไลด์ในงานนำเสนอ "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรม Zoom ใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรม Zoom ใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรม Zoom ใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรม Zoom ใหม่, หน่วยเป็นจุด. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) ที่อ้างอิงโดยเฟรม Zoom; ต้องเป็นของงานนำเสนอเดียวกันนี้. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | ภาพสำหรับสไลด์ที่อ้างอิง [IPPImage](../../com.aspose.slides/ippimage). |

**คืนค่า:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - The newly created [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

สร้างเฟรม Zoom ใหม่และแทรกเข้าไปในคอลเลกชันรูปทรงตามตำแหน่งที่ระบุ

--------------------

> ```
> ตัวอย่างนี้แสดงการสร้างและแทรกออบเจกต์ Zoom ที่ตำแหน่งดัชนีที่ระบุในคอลเลกชัน
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีศูนย์ฐานที่ต้องการแทรกเฟรม Zoom. |
| x | float | พิกัด x ของเฟรม Zoom ใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรม Zoom ใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรม Zoom ใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรม Zoom ใหม่, หน่วยเป็นจุด. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) ที่อ้างอิงโดยเฟรม Zoom. |

**คืนค่า:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - The newly created [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

สร้างเฟรม Zoom ใหม่พร้อมภาพที่กำหนดไว้ล่วงหน้าและแทรกเข้าไปในคอลเลกชันรูปทรงตามตำแหน่งที่ระบุ

--------------------

> ```
> ตัวอย่างนี้แสดงการสร้างและแทรกออบเจกต์ Zoom ที่ตำแหน่งดัชนีที่ระบุในคอลเลกชัน
>  (สมมติว่ามีสไลด์อย่างน้อยสองสไลด์ในงานนำเสนอ "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีศูนย์ฐานที่ต้องการแทรกเฟรม Zoom. |
| x | float | พิกัด x ของเฟรม Zoom ใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรม Zoom ใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรม Zoom ใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรม Zoom ใหม่, หน่วยเป็นจุด. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) ที่อ้างอิงโดยเฟรม Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | ภาพสำหรับสไลด์ที่อ้างอิง [IPPImage](../../com.aspose.slides/ippimage). |

**คืนค่า:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - The newly created [IZoomFrame](../../com.aspose.slides/izoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

สร้างเฟรม Section Zoom ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง

--------------------

> ```
> ตัวอย่างนี้แสดงการเพิ่มออบเจกต์ Section Zoom ไปที่ส่วนท้ายของคอลเลกชัน
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรม Section Zoom ใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรม Section Zoom ใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรม Section Zoom ใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรม Section Zoom ใหม่, หน่วยเป็นจุด. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) ที่อ้างอิงโดยเฟรม Section Zoom; ต้องเป็นของงานนำเสนอเดียวกันและต้องมีสไลด์อย่างน้อยหนึ่งสไลด์. |

**คืนค่า:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - The newly created [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดไว้ล่วงหน้าและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง

--------------------

> ```
> ตัวอย่างนี้แสดงการเพิ่มออบเจกต์ Section Zoom ไปที่ส่วนท้ายของคอลเลกชัน
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรม Section Zoom ใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรม Section Zoom ใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรม Section Zoom ใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรม Section Zoom ใหม่, หน่วยเป็นจุด. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) ที่อ้างอิงโดยเฟรม Section Zoom; ต้องเป็นของงานนำเสนอเดียวกันและต้องมีสไลด์อย่างน้อยหนึ่งสไลด์. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) ที่จะแสดงภายในเฟรม Section Zoom. |

**คืนค่า:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - The newly created [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

สร้างเฟรม Section Zoom ใหม่และแทรกเข้าไปในคอลเลกชันรูปทรงตามตำแหน่งที่ระบุ

--------------------

> ```
> ตัวอย่างนี้แสดงการสร้างและแทรกออบเจกต์ Section Zoom ที่ตำแหน่งดัชนีที่ระบุในคอลเลกชัน
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีศูนย์ฐานที่ต้องการแทรกเฟรม Section Zoom. |
| x | float | พิกัด x ของเฟรม Section Zoom ใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรม Section Zoom ใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรม Section Zoom ใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรม Section Zoom ใหม่, หน่วยเป็นจุด. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) ที่อ้างอิงโดยเฟรม Section Zoom; ต้องเป็นของงานนำเสนอเดียวกันและต้องมีสไลด์อย่างน้อยหนึ่งสไลด์. |

**คืนค่า:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - The newly created [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดไว้ล่วงหน้าและแทรกเข้าไปในคอลเลกชันรูปทรงตามตำแหน่งที่ระบุ

--------------------

> ```
> ตัวอย่างนี้แสดงการสร้างและแทรกออบเจกต์ Section Zoom ที่ตำแหน่งดัชนีที่ระบุในคอลเลกชัน
>  (สมมติว่ามีส่วนอย่างน้อยสองส่วนในงานนำเสนอ "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีศูนย์ฐานที่ต้องการแทรกเฟรม Section Zoom. |
| x | float | พิกัด x ของเฟรม Section Zoom ใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรม Section Zoom ใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรม Section Zoom ใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรม Section Zoom ใหม่, หน่วยเป็นจุด. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) ที่อ้างอิงโดยเฟรม Section Zoom; ต้องเป็นของงานนำเสนอเดียวกันและต้องมีสไลด์อย่างน้อยหนึ่งสไลด์. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | ภาพที่จะแสดงภายในเฟรม Section Zoom. |

**คืนค่า:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - The newly created [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

สร้างเฟรม Summary Zoom ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง

--------------------

> ```
> ตัวอย่างนี้แสดงการเพิ่มออบเจกต์ Summary Zoom ไปที่ส่วนท้ายของคอลเลกชัน
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด x ของเฟรม Summary Zoom ใหม่, หน่วยเป็นจุด. |
| y | float | พิกัด y ของเฟรม Summary Zoom ใหม่, หน่วยเป็นจุด. |
| width | float | ความกว้างของเฟรม Summary Zoom ใหม่, หน่วยเป็นจุด. |
| height | float | ความสูงของเฟรม Summary Zoom ใหม่, หน่วยเป็นจุด. |
เมธอดนี้สร้างกรอบ Summary Zoom ที่รวบรวมลิงก์สรุปสำหรับทุกส่วนในงานนำเสนอ. |

**คืนค่า:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - อ็อบเจ็กต์ที่สร้างใหม่ [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

สร้างกรอบ Summary Zoom ใหม่และแทรกลงในคอลเลกชัน shape ที่ตำแหน่งที่ระบุ

--------------------

> ```
> ตัวอย่างนี้แสดงการสร้างและแทรกออบเจกต์ Summary Zoom ที่ตำแหน่งดัชนีที่กำหนดในคอลเลกชัน
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
| index | int | ดัชนีที่เริ่มจากศูนย์ซึ่งจะใช้เพื่อแทรกกรอบ Summary Zoom |
| x | float | ค่าพิกัด x ของกรอบ Summary Zoom ใหม่, หน่วยเป็นพอยต์ |
| y | float | ค่าพิกัด y ของกรอบ Summary Zoom ใหม่, หน่วยเป็นพอยต์ |
| width | float | ความกว้างของกรอบ Summary Zoom ใหม่, หน่วยเป็นพอยต์ |
| height | float | ความสูงของกรอบ Summary Zoom ใหม่, หน่วยเป็นพอยต์ |

--------------------

เมธอดนี้สร้างกรอบ Summary Zoom ที่รวบรวมลิงก์สรุปสำหรับทุกส่วนในงานนำเสนอ. |

**คืนค่า:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - อ็อบเจ็กต์ที่สร้างใหม่ [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

สร้างเฟรมวิดีโอใหม่และเพิ่มเข้าไปที่ท้ายคอลเลกชัน shape

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | ค่าพิกัด x ของเฟรมวิดีโอใหม่, หน่วยเป็นพอยต์ |
| y | float | ค่าพิกัด y ของเฟรมวิดีโอใหม่, หน่วยเป็นพอยต์ |
| width | float | ความกว้างของเฟรมวิดีโอใหม่, หน่วยเป็นพอยต์ |
| height | float | ความสูงของเฟรมวิดีโอใหม่, หน่วยเป็นพอยต์ |
| fname | java.lang.String | พาธหรือชื่อไฟล์วิดีโอที่จะฝัง |

**คืนค่า:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - อ็อบเจ็กต์ที่สร้างใหม่ [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

สร้างเฟรมวิดีโอใหม่และเพิ่มเข้าไปที่ท้ายคอลเลกชัน shape

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | ค่าพิกัด x ของเฟรมวิดีโอใหม่, หน่วยเป็นพอยต์ |
| y | float | ค่าพิกัด y ของเฟรมวิดีโอใหม่, หน่วยเป็นพอยต์ |
| width | float | ความกว้างของเฟรมวิดีโอใหม่, หน่วยเป็นพอยต์ |
| height | float | ความสูงของเฟรมวิดีโอใหม่, หน่วยเป็นพอยต์ |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) ที่จะฝังในเฟรมวิดีโอ |

**คืนค่า:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - อ็อบเจ็กต์ที่สร้างใหม่ [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

สร้างเฟรมวิดีโอใหม่และแทรกลงในคอลเลกชัน shape ที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ซึ่งจะใช้เพื่อแทรกเฟรมวิดีโอ |
| x | float | ค่าพิกัด x ของเฟรมวิดีโอใหม่, หน่วยเป็นพอยต์ |
| y | float | ค่าพิกัด y ของเฟรมวิดีโอใหม่, หน่วยเป็นพอยต์ |
| width | float | ความกว้างของเฟรมวิดีโอใหม่, หน่วยเป็นพอยต์ |
| height | float | ความสูงของเฟรมวิดีโอใหม่, หน่วยเป็นพอยต์ |
| fname | java.lang.String | พาธหรือชื่อไฟล์วิดีโอที่จะฝัง |

**คืนค่า:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - อ็อบเจ็กต์ที่สร้างใหม่ [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับแทร็ก CD แล้วเพิ่มเข้าไปที่ท้ายคอลเลกชัน shape

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | ค่าพิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| y | float | ค่าพิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| width | float | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| height | float | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |

**คืนค่า:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - อ็อบเจ็กต์ที่สร้างใหม่ [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับแทร็ก CD แล้วแทรกลงในคอลเลกชัน shape ที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ซึ่งจะใช้เพื่อแทรกเฟรมเสียง |
| x | float | ค่าพิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| y | float | ค่าพิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| width | float | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| height | float | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |

**คืนค่า:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - อ็อบเจ็กต์ที่สร้างใหม่ [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับไฟล์เสียงภายนอกแล้วเพิ่มเข้าไปที่ท้ายคอลเลกชัน shape

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | ค่าพิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| y | float | ค่าพิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| width | float | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| height | float | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| fname | java.lang.String | พาธหรือชื่อไฟล์เสียงภายนอกที่จะเชื่อมโยง |

**คืนค่า:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - อ็อบเจ็กต์ที่สร้างใหม่ [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับไฟล์เสียงภายนอกแล้วแทรกลงในคอลเลกชัน shape ที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ซึ่งจะใช้เพื่อแทรกเฟรมเสียง |
| x | float | ค่าพิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| y | float | ค่าพิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| width | float | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| height | float | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| fname | java.lang.String | พาธหรือชื่อไฟล์เสียงภายนอกที่จะเชื่อมโยง |

**คืนค่า:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - อ็อบเจ็กต์ที่สร้างใหม่ [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

สร้างเฟรมเสียงใหม่พร้อมไฟล์ WAV ฝังอยู่แล้วและเพิ่มเข้าไปที่ท้ายคอลเลกชัน shape  ไฟล์เสียงที่ฝังจะถูกเพิ่มไปยังคอลเลกชัน Presentation.Audios

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | ค่าพิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| y | float | ค่าพิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| width | float | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| height | float | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| audio_stream | java.io.InputStream | สตรีมอินพุตที่มีข้อมูลเสียง WAV เพื่อฝัง |

**คืนค่า:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - อ็อบเจ็กต์ที่สร้างใหม่ [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

สร้างเฟรมเสียงใหม่และเพิ่มเข้าไปที่ท้ายคอลเลกชัน shape โดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | ค่าพิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| y | float | ค่าพิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| width | float | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| height | float | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| audio | [IAudio](../../com.aspose.slides/iaudio) | อินสแตนซ์ [IAudio](../../com.aspose.slides/iaudio) จากคอลเลกชัน Presentation.Audios |

**คืนค่า:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - อ็อบเจ็กต์ที่สร้างใหม่ [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

สร้างเฟรมเสียงใหม่พร้อมไฟล์ WAV ฝังอยู่แล้วและแทรกลงในคอลเลกชัน shape ที่ตำแหน่งที่ระบุ  ไฟล์เสียงที่ฝังจะถูกเพิ่มไปยังคอลเลกชัน Presentation.Audios

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ซึ่งจะใช้เพื่อแทรกเฟรมเสียง |
| x | float | ค่าพิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| y | float | ค่าพิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| width | float | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| height | float | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| audio_stream | java.io.InputStream | สตรีมอินพุตที่มีข้อมูลเสียง WAV เพื่อฝัง |

**คืนค่า:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - อ็อบเจ็กต์ที่สร้างใหม่ [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

สร้างเฟรมเสียงใหม่และแทรกลงในคอลเลกชัน shape ที่ตำแหน่งที่ระบุโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ซึ่งจะใช้เพื่อแทรกเฟรมเสียง |
| x | float | ค่าพิกัด x ของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| y | float | ค่าพิกัด y ของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| width | float | ความกว้างของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| height | float | ความสูงของเฟรมเสียงใหม่, หน่วยเป็นพอยต์ |
| audio | [IAudio](../../com.aspose.slides/iaudio) | อินสแตนซ์ [IAudio](../../com.aspose.slides/iaudio) จากคอลเลกชัน Presentation.Audios เพื่อฝัง |

**คืนค่า:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - อ็อบเจ็กต์ที่สร้างใหม่ [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

คืนค่าดัชนีที่เริ่มจากศูนย์ของการปรากฏครั้งแรกของ shape ที่ระบุในคอลเลกชัน

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | shape ที่ต้องการค้นหาในคอลเลกชัน |

**คืนค่า:**  
int - ดัชนีที่เริ่มจากศูนย์ของการปรากฏครั้งแรกของ shape ในคอลเลกชัน shape หากพบ; มิฉะนั้น \\u20131.

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

สร้างและคืนค่าอาร์เรย์ที่บรรจุ shape ทั้งหมด

**คืนค่า:**  
com.aspose.slides.IShape[] - อาร์เรย์ของวัตถุ [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

สร้างและคืนค่าอาร์เรย์ที่บรรจุ shape ทั้งหมดในช่วงที่ระบุ

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | ดัชนีของ shape แรกที่ต้องการคืนค่า |
| count | int | จำนวน shape ที่ต้องการคืนค่า |

**คืนค่า:**  
com.aspose.slides.IShape[] - อาร์เรย์ของวัตถุ [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

ย้าย shape ที่ระบุไปตำแหน่งใหม่ภายในคอลเลกชัน shape

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีเป้าหมายที่เริ่มจากศูนย์ที่ shape จะถูกวาง |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) ที่ต้องการย้ายภายในคอลเลกชัน |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

ย้าย shape หลายรายการภายในคอลเลกชัน shape โดยเริ่มวางจากดัชนีที่ระบุ

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีเป้าหมายที่เริ่มจากศูนย์ที่ shape แรกจะถูกวาง; shape ถัดไปจะวางต่อเนื่องตามลำดับที่ให้ |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | หนึ่งหรือหลายอินสแตนซ์ [IShape](../../com.aspose.slides/ishape) ที่ต้องการย้ายภายในคอลเลกชัน |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

สร้าง auto shape ใหม่ด้วยการฟอร์แมตค่าเริ่มต้นและเพิ่มเข้าไปที่ท้ายคอลเลกชัน shape

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) ของ auto shape ที่จะเพิ่ม |

| x | float | พิกัด x ของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |
| y | float | พิกัด y ของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |
| width | float | ความกว้างของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |
| height | float | ความสูงของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |

**คืนค่า:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - ที่สร้างใหม่ [IAutoShape](../../com.aspose.slides/iautoshape).  

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}  
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

สร้างอัตโนมัติรูปร่างใหม่และเพิ่มลงในส่วนสุดท้ายของคอลเลกชันรูปร่าง, โดยอาจเริ่มต้นด้วยการจัดรูปแบบแม่แบบเริ่มต้น.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) ของอัตโนมัติรูปร่างที่จะเพิ่ม. |
| x | float | พิกัด x ของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |
| y | float | พิกัด y ของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |
| width | float | ความกว้างของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |
| height | float | ความสูงของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |
| createFromTemplate | boolean | True เพื่อใช้สไตล์แม่แบบเริ่มต้น (สไตล์ง่าย, ข้อความกึ่งกลาง, และชื่อไม่ว่าง) กับรูปร่างใหม่; false เพื่อสร้างรูปร่างโดยตั้งค่าทุกคุณสมบัติเป็นค่าเริ่มต้น. |

**คืนค่า:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - ที่สร้างใหม่ [IAutoShape](../../com.aspose.slides/iautoshape).  

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}  
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

สร้างอัตโนมัติรูปร่างสี่เหลี่ยมเพื่อเป็นที่เก็บเนื้อหาคณิตศาสตร์และเพิ่มลงในส่วนสุดท้ายของคอลเลกชันรูปร่าง.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด x ของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |
| y | float | พิกัด y ของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |
| width | float | ความกว้างของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |
| height | float | ความสูงของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |

**คืนค่า:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - ที่สร้างใหม่ [IAutoShape](../../com.aspose.slides/iautoshape).  

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}  
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

สร้างอัตโนมัติรูปร่างใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่ง index ที่ระบุ, พร้อมใช้สไตล์แม่แบบเริ่มต้น.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีฐานศูนย์ที่ต้องการแทรกอัตโนมัติรูปร่างใหม่. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) ของอัตโนมัติรูปร่างที่จะแทรก. |
| x | float | พิกัด x ของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |
| y | float | พิกัด y ของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |
| width | float | ความกว้างของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |
| height | float | ความสูงของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |

**คืนค่า:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - ที่สร้างใหม่ [IAutoShape](../../com.aspose.slides/iautoshape).  

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}  
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

สร้างอัตโนมัติรูปร่างใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่ง index ที่ระบุ, โดยอาจเริ่มต้นด้วยสไตล์แม่แบบเริ่มต้น.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีฐานศูนย์ที่ต้องการแทรกอัตโนมัติรูปร่าง. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) ของอัตโนมัติรูปร่างที่จะแทรก. |
| x | float | พิกัด x ของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |
| y | float | พิกัด y ของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |
| width | float | ความกว้างของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |
| height | float | ความสูงของกรอบรูปร่าง, มีหน่วยเป็นพอยท์. |
| createFromTemplate | boolean | True เพื่อใช้สไตล์แม่แบบเริ่มต้น (รวมชื่อไม่ว่าง, สไตล์ง่าย, และข้อความกึ่งกลาง); false เพื่อสร้างรูปร่างโดยตั้งค่าทุกคุณสมบัติเป็นค่าเริ่มต้น. |

**คืนค่า:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - ที่สร้างใหม่ [IAutoShape](../../com.aspose.slides/iautoshape).  

### addGroupShape() {#addGroupShape--}  
```
public abstract IGroupShape addGroupShape()
```

สร้างกลุ่มรูปร่างเปล่าใหม่และเพิ่มลงในส่วนสุดท้ายของคอลเลกชันรูปร่าง. กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดีกับรูปร่างใด ๆ ที่เพิ่มเข้าไป.

**คืนค่า:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - ที่สร้างใหม่ [IGroupShape](../../com.aspose.slides/igroupshape).  

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}  
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

สร้างกลุ่มรูปร่างใหม่, แปลงภาพ SVG ที่ระบุเป็นรูปร่างแยกส่วน, แล้วเพิ่มกลุ่มที่ได้ลงในส่วนสุดท้ายของคอลเลกชันรูปร่าง.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) ที่มีเนื้อหาเวกเตอร์เพื่อแปลงเป็นรูปร่าง. |
| x | float | พิกัด x ของกรอบกลุ่ม, มีหน่วยเป็นพอยท์. |
| y | float | พิกัด y ของกรอบกลุ่ม, มีหน่วยเป็นพอยท์. |
| width | float | ความกว้างของกรอบกลุ่ม, มีหน่วยเป็นพอยท์. |
| height | float | ความสูงของกรอบกลุ่ม, มีหน่วยเป็นพอยท์. |

**คืนค่า:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - ที่สร้างใหม่ [IGroupShape](../../com.aspose.slides/igroupshape).  

### insertGroupShape(int index) {#insertGroupShape-int-}  
```
public abstract IGroupShape insertGroupShape(int index)
```

สร้างกลุ่มรูปร่างเปล่าใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่ง index ที่ระบุ. กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดิกับรูปร่างใด ๆ ที่เพิ่มเข้าไป.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีฐานศูนย์ที่ต้องการแทรกกลุ่มรูปร่าง. |

**คืนค่า:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - ที่สร้างใหม่ [IGroupShape](../../com.aspose.slides/igroupshape).  

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}  
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

สร้างรูปร่างเชื่อมต่อใหม่ด้วยสไตล์แม่แบบเริ่มต้นและเพิ่มลงในส่วนสุดท้ายของคอลเลกชันรูปร่าง.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) ของรูปร่างเชื่อมต่อที่จะเพิ่ม. |
| x | float | พิกัด x ของกรอบเชื่อมต่อ, มีหน่วยเป็นพอยท์. |
| y | float | พิกัด y ของกรอบเชื่อมต่อ, มีหน่วยเป็นพอยท์. |
| width | float | ความกว้างของกรอบเชื่อมต่อ, มีหน่วยเป็นพอยท์. |
| height | float | ความสูงของกรอบเชื่อมต่อ, มีหน่วยเป็นพอยท์. |

**คืนค่า:**  
[IConnector](../../com.aspose.slides/iconnector) - ที่สร้างใหม่ [IConnector](../../com.aspose.slides/iconnector).  

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}  
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

สร้างรูปร่างเชื่อมต่อใหม่และเพิ่มลงในส่วนสุดท้ายของคอลเลกชันรูปร่าง, โดยอาจใช้สไตล์แม่แบบเริ่มต้น.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) ของรูปร่างเชื่อมต่อที่จะสร้าง. |
| x | float | พิกัด x ของกรอบเชื่อมต่อ, มีหน่วยเป็นพอยท์. |
| y | float | พิกัด y ของกรอบเชื่อมต่อ, มีหน่วยเป็นพอยท์. |
| width | float | ความกว้างของกรอบเชื่อมต่อ, มีหน่วยเป็นพอยท์. |
| height | float | ความสูงของกรอบเชื่อมต่อ, มีหน่วยเป็นพอยท์. |
| createFromTemplate | boolean | True เพื่อใช้สไตล์แม่แบบเริ่มต้น (ชื่อไม่ว่าง, สไตล์ง่าย); false เพื่อสร้างเชื่อมต่อโดยใช้ค่าคุณสมบัติดีฟอลต์. |

**คืนค่า:**  
[IConnector](../../com.aspose.slides/iconnector) - ที่สร้างใหม่ [IConnector](../../com.aspose.slides/iconnector).  

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}  
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

สร้างรูปร่างเชื่อมต่อใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่ง index ที่ระบุ, พร้อมใช้สไตล์แม่แบบเริ่มต้น.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีฐานศูนย์ที่ต้องการแทรกรูปร่างเชื่อมต่อ. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) ของรูปร่างเชื่อมต่อที่จะแทรก. |
| x | float | พิกัด x ของกรอบเชื่อมต่อ, มีหน่วยเป็นพอยท์. |
| y | float | พิกัด y ของกรอบเชื่อมต่อ, มีหน่วยเป็นพอยท์. |
| width | float | ความกว้างของกรอบเชื่อมต่อ, มีหน่วยเป็นพอยท์. |
| height | float | ความสูงของกรอบเชื่อมต่อ, มีหน่วยเป็นพอยท์. |

**คืนค่า:**  
[IConnector](../../com.aspose.slides/iconnector) - ที่สร้างใหม่ [IConnector](../../com.aspose.slides/iconnector).  

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}  
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

สร้างรูปร่างเชื่อมต่อใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่ง index ที่ระบุ, โดยอาจใช้สไตล์แม่แบบเริ่มต้น.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีฐานศูนย์ที่ต้องการแทรกรูปร่างเชื่อมต่อ. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) ของรูปร่างเชื่อมต่อที่จะแทรก. |
| x | float | พิกัด x ของกรอบเชื่อมต่อ, มีหน่วยเป็นพอยท์. |
| y | float | พิกัด y ของกรอบเชื่อมต่อ, มีหน่วยเป็นพอยท์. |
| width | float | ความกว้างของกรอบเชื่อมต่อ, มีหน่วยเป็นพอยท์. |
| height | float | ความสูงของกรอบเชื่อมต่อ, มีหน่วยเป็นพอยท์. |
| createFromTemplate | boolean | True เพื่อใช้สไตล์แม่แบบเริ่มต้น (ชื่อไม่ว่าง, สไตล์ง่าย); false เพื่อสร้างเชื่อมต่อโดยใช้ค่าคุณสมบัติดีฟอลต์. |

**คืนค่า:**  
[IConnector](../../com.aspose.slides/iconnector) - ที่สร้างใหม่ [IConnector](../../com.aspose.slides/iconnector).  

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}  
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

สร้างกรอบรูปภาพใหม่ที่บรรจุภาพที่ระบุและเพิ่มลงในส่วนสุดท้ายของคอลเลกชันรูปร่าง.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeType | int | ระบุประเภทรูปร่างที่อยู่ใน [ShapeType](../../com.aspose.slides/shapetype), ยกเว้นรูปแบบเส้นทั้งหมด:  

ShapeType.Line,  

ShapeType.StraightConnector1,  

ShapeType.BentConnector2,  

ShapeType.BentConnector3,  

ShapeType.BentConnector4,  

ShapeType.BentConnector5,  

ShapeType.CurvedConnector2,  

ShapeType.CurvedConnector3,  

ShapeType.CurvedConnector4,  

ShapeType.CurvedConnector5. |
| x | float | พิกัด x ของกรอบรูปภาพ, มีหน่วยเป็นพอยท์. |
| y | float | พิกัด y ของกรอบรูปภาพ, มีหน่วยเป็นพอยท์. |
| width | float | ความกว้างของกรอบรูปภาพ, มีหน่วยเป็นพอยท์. |
| height | float | ความสูงของกรอบรูปภาพ, มีหน่วยเป็นพอยท์. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) ที่จะแสดงในกรอบรูปภาพ. |

**คืนค่า:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - ที่สร้างใหม่ [IPictureFrame](../../com.aspose.slides/ipictureframe).  

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}  
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

สร้างกรอบรูปภาพใหม่ที่บรรจุภาพที่ระบุและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่ง index ที่ระบุ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีฐานศูนย์ที่ต้องการแทรกกรอบรูปภาพ. |
| shapeType | int | ระบุประเภทรูปร่างที่อยู่ใน [ShapeType](../../com.aspose.slides/shapetype), ยกเว้นรูปแบบเส้นทั้งหมด:  

ShapeType.Line,  

ShapeType.StraightConnector1,  

ShapeType.BentConnector2,  

ShapeType.BentConnector3,  

ShapeType.BentConnector4,  

ShapeType.BentConnector5,  

ShapeType.CurvedConnector2,  

ShapeType.CurvedConnector3,  

ShapeType.CurvedConnector4,  

ShapeType.CurvedConnector5. |
| x | float | พิกัด x ของกรอบรูปภาพ, มีหน่วยเป็นพอยท์. |
| y | float | พิกัด y ของกรอบรูปภาพ, มีหน่วยเป็นพอยท์. |
| width | float | ความกว้างของกรอบรูปภาพ, มีหน่วยเป็นพอยท์. |
| height | float | ความสูงของกรอบรูปภาพ, มีหน่วยเป็นพอยท์. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) ที่จะแสดงในกรอบรูปภาพ. |

**คืนค่า:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - ที่สร้างใหม่ [IPictureFrame](../../com.aspose.slides/ipictureframe).  

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}  
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

สร้างตารางใหม่และเพิ่มลงในส่วนสุดท้ายของคอลเลกชันรูปร่าง.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด x ของตาราง, มีหน่วยเป็นพอยท์. |
| y | float | พิกัด y ของตาราง, มีหน่วยเป็นพอยท์. |
| columnWidths | double[] | อาเรย์ของค่า double ที่แทนความกว้างของคอลัมน์ของตาราง, มีหน่วยเป็นพอยท์. |
| rowHeights | double[] | อาเรย์ของค่า double ที่แทนความสูงของแถวของตาราง, มีหน่วยเป็นพอยท์. |

**คืนค่า:**  
[ITable](../../com.aspose.slides/itable) - ที่สร้างใหม่ [ITable](../../com.aspose.slides/itable).  

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}  
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
Creates a new table and inserts it into the shape collection at the specified index.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ใช้ในการแทรกตาราง |
| x | float | พิกัด x ของตาราง หน่วยเป็นพอยต์ |
| y | float | พิกัด y ของตาราง หน่วยเป็นพอยต์ |
| columnWidths | double[] | อาร์เรย์ของค่าชนิด double ที่แสดงความกว้างของคอลัมน์ของตาราง หน่วยเป็นพอยต์ |
| rowHeights | double[] | อาร์เรย์ของค่าชนิด double ที่แสดงความสูงของแถวของตาราง หน่วยเป็นพอยต์ |

**ผลลัพธ์:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) ที่สร้างใหม่

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Removes the shape at the specified index from the shape collection.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ของรูปร่างที่ต้องการลบ |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Removes the first occurrence of the specified shape from the shape collection.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) ที่ต้องการลบ |

### clear() {#clear--}
```
public abstract void clear()
```

Removes all shapes from the shape collection.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Creates a copy of the specified shape and adds it to the end of the shape collection.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | รูปร่างที่ต้องการทำสำเนา |
| x | float | พิกัด x ของกรอบรูปร่างที่ทำสำเนา หน่วยเป็นพอยต์ |
| y | float | พิกัด y ของกรอบรูปร่างที่ทำสำเนา หน่วยเป็นพอยต์ |
| width | float | ความกว้างของกรอบรูปร่างที่ทำสำเนา หน่วยเป็นพอยต์ |
| height | float | ความสูงของกรอบรูปร่างที่ทำสำเนา หน่วยเป็นพอยต์ |

**ผลลัพธ์:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) ที่สร้างใหม่

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the  sourceShape .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) ที่ต้องการทำสำเนา |
| x | float | พิกัด x ของกรอบรูปร่างที่ทำสำเนา หน่วยเป็นพอยต์ |
| y | float | พิกัด y ของกรอบรูปร่างที่ทำสำเนา หน่วยเป็นพอยต์ |

**ผลลัพธ์:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) ที่สร้างใหม่

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original's position and size.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) ที่ต้องการทำสำเนา |

**ผลลัพธ์:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) ที่สร้างใหม่

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Creates a copy of the specified shape and inserts it into the shape collection at the specified index.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ใช้ในการแทรกรูปร่างที่ทำสำเนา |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) ที่ต้องการทำสำเนา |
| x | float | พิกัด x ของกรอบรูปร่างที่ทำสำเนา หน่วยเป็นพอยต์ |
| y | float | พิกัด y ของกรอบรูปร่างที่ทำสำเนา หน่วยเป็นพอยต์ |
| width | float | ความกว้างของกรอบรูปร่างที่ทำสำเนา หน่วยเป็นพอยต์ |
| height | float | ความสูงของกรอบรูปร่างที่ทำสำเนา หน่วยเป็นพอยต์ |

**ผลลัพธ์:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) ที่สร้างใหม่

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the  sourceShape .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ใช้ในการแทรกรูปร่างที่ทำสำเนา |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) ที่ต้องการทำสำเนา |
| x | float | พิกัด x ของกรอบรูปร่างที่ทำสำเนา หน่วยเป็นพอยต์ |
| y | float | พิกัด y ของกรอบรูปร่างที่ทำสำเนา หน่วยเป็นพอยต์ |

**ผลลัพธ์:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) ที่สร้างใหม่

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original's position and size.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ใช้ในการแทรกรูปร่างที่ทำสำเนา |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) ที่ต้องการทำสำเนา |

**ผลลัพธ์:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) ที่สร้างใหม่