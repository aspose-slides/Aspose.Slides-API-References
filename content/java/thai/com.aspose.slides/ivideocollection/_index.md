---
title: IVideoCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงคอลเล็กชันของอ็อบเจ็กต์ Video.
type: docs
url: /th/com.aspose.slides/ivideocollection/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

แสดงถึงคอลเล็กชันของอ็อบเจ็กต์ Video.
## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Adds a copy of an video file from an another presentation. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Creates and adds a video to a presentation from stream. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Creates and adds a video to a presentation from byte array. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```

ดึงเอาอิลเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IVideo](../../com.aspose.slides/ivideo).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```

เพิ่มสำเนาของไฟล์วิดีโอจากการนำเสนออื่น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | วิดีโอต้นฉบับ. |

**ผลลัพธ์:**
[IVideo](../../com.aspose.slides/ivideo) - วิดีโอที่เพิ่ม.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

สร้างและเพิ่มวิดีโอลงในการนำเสนอจากสตรีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมเพื่อเพิ่มไฟล์วิดีโอจาก. |
| loadingStreamBehavior | int | พฤติกรรมที่จะนำไปใช้กับสตรีม. |

**ผลลัพธ์:**
[IVideo](../../com.aspose.slides/ivideo) - เพิ่ม [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```

สร้างและเพิ่มวิดีโอลงในการนำเสนอจากอาร์เรย์ไบต์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| videoData | byte[] | ไบต์ของวิดีโอ. |

**ผลลัพธ์:**
[IVideo](../../com.aspose.slides/ivideo) - วิดีโอที่เพิ่ม.