---
title: VideoCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของคอลเลกชันของอ็อบเจ็กต์ Video.
type: docs
url: /th/com.aspose.slides/videocollection/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)  
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

เป็นตัวแทนของคอลเลกชันของอ็อบเจ็กต์ Video.

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | คืนค่าจำนวนไฟล์วิดีโอในคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | เพิ่มสำเนาของไฟล์วิดีโอจากงานนำเสนออื่น. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | สร้างและเพิ่มวิดีโอไปยังงานนำเสนอจากสตรีม. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | สร้างและเพิ่มวิดีโอไปยังงานนำเสนอจากอาร์เรย์ไบต์. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกวิดีโอลงในอาร์เรย์ที่กำหนดโดยเริ่มจากตำแหน่งที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันนี้ถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) หรือไม่. |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากฐานการซิงโครไนซ์. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่ทำการวนซ้ำผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |

### size() {#size--}
```
public final int size()
```

คืนค่าจำนวนไฟล์วิดีโอในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IVideo](../../com.aspose.slides/ivideo).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**  
[IVideo](../../com.aspose.slides/ivideo)

### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```

เพิ่มสำเนาของไฟล์วิดีโอจากงานนำเสนออื่น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | วิดีโอต้นฉบับ. |

**คืนค่า:**  
[IVideo](../../com.aspose.slides/ivideo) - วิดีโอที่เพิ่ม.

### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

สร้างและเพิ่มวิดีโอไปยังงานนำเสนอจากสตรีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมที่ใช้ในการเพิ่มไฟล์วิดีโอ. |
| loadingStreamBehavior | int | พฤติกรรมที่จะนำไปใช้กับสตรีม. |

**คืนค่า:**  
[IVideo](../../com.aspose.slides/ivideo) - วิดีโอที่เพิ่ม [IVideo](../../com.aspose.slides/ivideo).

### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

สร้างและเพิ่มวิดีโอไปยังงานนำเสนอจากอาร์เรย์ไบต์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| videoData | byte[] | ไบต์ของวิดีโอ. |

**คืนค่า:**  
[IVideo](../../com.aspose.slides/ivideo) - วิดีโอที่เพิ่ม.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกวิดีโอลงในอาร์เรย์ที่กำหนดโดยเริ่มจากตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์. |
| index | int | ดัชนี. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันนี้ถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) หรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่ารากฐานการซิงโครไนซ์. อ่านอย่างเดียว Object.

**คืนค่า:**  
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

คืนค่า enumerator ที่ทำการวนซ้ำผ่านคอลเลกชัน.

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - An java.util.Iterator for the entire collection.