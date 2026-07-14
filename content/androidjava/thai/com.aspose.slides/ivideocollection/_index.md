---
title: IVideoCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นคอลเลกชันของอ็อบเจ็กต์ Video.
type: docs
url: /th/com.aspose.slides/ivideocollection/
---
**อินเทอร์เฟซที่นำไปใช้งานทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

เป็นคอลเลกชันของอ็อบเจ็กต์ Video.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | เพิ่มสำเนาไฟล์วิดีโอจากการนำเสนออื่น. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | สร้างและเพิ่มวิดีโอลงในงานนำเสนอจากสตรีม. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | สร้างและเพิ่มวิดีโอลงในงานนำเสนอจากอาร์เรย์ไบต์. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```

ดึงองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IVideo](../../com.aspose.slides/ivideo).

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

เพิ่มสำเนาไฟล์วิดีโอจากการนำเสนออื่น.

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

สร้างและเพิ่มวิดีโอลงในงานนำเสนอจากสตรีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมที่ใช้เพิ่มไฟล์วิดีโอจาก. |
| loadingStreamBehavior | int | พฤติกรรมที่จะนำไปใช้กับสตรีม. |

**ผลลัพธ์:**
[IVideo](../../com.aspose.slides/ivideo) - เพิ่ม [IVideo](../../com.aspose.slides/ivideo).

### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```

สร้างและเพิ่มวิดีโอลงในงานนำเสนอจากอาร์เรย์ไบต์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| videoData | byte[] | ไบต์ของวิดีโอ. |

**ผลลัพธ์:**
[IVideo](../../com.aspose.slides/ivideo) - วิดีโอที่เพิ่ม.