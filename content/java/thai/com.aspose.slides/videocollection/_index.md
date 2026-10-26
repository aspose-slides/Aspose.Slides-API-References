---
title: VideoCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงคอลเลกชันของอ็อบเจกต์ Video.
type: docs
url: /th/com.aspose.slides/videocollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

แสดงถึงคอลเลกชันของอ็อบเจกต์ Video.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | ส่งคืนจำนวนไฟล์วิดีโอในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | แกะค่าที่ตำแหน่งที่ระบุ |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | เพิ่มสำเนาไฟล์วิดีโอจากงานนำเสนออื่น |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | สร้างและเพิ่มวิดีโอลงในงานนำเสนอจากสตรีม |
| [addVideo(byte[] videoData)](#addVideo-byte---) | สร้างและเพิ่มวิดีโอลงในงานนำเสนอจากอาร์เรย์ไบต์ |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกวิดีโอไปยังอาร์เรย์ที่ระบุเริ่มจากตำแหน่งที่กำหนด |
| [isSynchronized()](#isSynchronized--) | ส่งคืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันนี้เป็นแบบซิงโครไนซ์ (thread-safe) |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืนรากที่ใช้สำหรับซิงโครไนซ์ |
| [iterator()](#iterator--) | ส่งคืนอีเทอเรเตอร์สำหรับวนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | ส่งคืนอีเทอเรเตอร์แบบ Java สำหรับคอลเลกชันทั้งหมด |
### size() {#size--}
```
public final int size()
```

ส่งคืนจำนวนไฟล์วิดีโอในคอลเลกชัน. อ่านอย่างเดียว int.

**ผลลัพธ์:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

แกะค่าที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IVideo](../../com.aspose.slides/ivideo).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```

เพิ่มสำเนาไฟล์วิดีโอจากงานนำเสนออื่น

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | วิดีโอต้นฉบับ |

**ผลลัพธ์:**
[IVideo](../../com.aspose.slides/ivideo) - วิดีโอที่เพิ่มแล้ว
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

สร้างและเพิ่มวิดีโอลงในงานนำเสนอจากสตรีม

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมที่ใช้เพิ่มไฟล์วิดีโอ |
| loadingStreamBehavior | int | พฤติกรรมที่ใช้กับสตรีม |

**ผลลัพธ์:**
[IVideo](../../com.aspose.slides/ivideo) - [IVideo](../../com.aspose.slides/ivideo) ที่เพิ่มแล้ว
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

สร้างและเพิ่มวิดีโอลงในงานนำเสนอจากอาร์เรย์ไบต์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| videoData | byte[] | ไบต์ของวิดีโอ |

**ผลลัพธ์:**
[IVideo](../../com.aspose.slides/ivideo) - วิดีโอที่เพิ่มแล้ว
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกวิดีโอไปยังอาร์เรย์ที่ระบุเริ่มจากตำแหน่งที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์ |
| index | int | ดัชนี |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ส่งคืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันนี้เป็นแบบซิงโครไนซ์ (thread-safe). อ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ส่งคืนรากที่ใช้สำหรับซิงโครไนซ์. อ่านอย่างเดียว Object.

**ผลลัพธ์:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

ส่งคืนอีเทอเรเตอร์สำหรับวนซ้ำผ่านคอลเลกชัน

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - IGenericEnumerator ที่สามารถใช้วนผ่านคอลเลกชันได้
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

ส่งคืนอีเทอเรเตอร์แบบ Java สำหรับคอลเลกชันทั้งหมด

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด