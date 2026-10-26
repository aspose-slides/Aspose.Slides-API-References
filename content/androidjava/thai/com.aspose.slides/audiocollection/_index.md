---
title: AudioCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: แสดงถึงคอลเลกชันของไฟล์เสียงฝังอยู่.
type: docs
url: /th/com.aspose.slides/audiocollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่นำมาใช้งานทั้งหมด:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

แสดงถึงคอลเลกชันของไฟล์เสียงฝังอยู่.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | ส่งคืนจำนวนไฟล์เสียงในคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | รับอิลิเมนต์ที่ตำแหน่งที่ระบุ. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | เพิ่มสำเนาของไฟล์เสียงจากงานนำเสนออื่น. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | สร้างและเพิ่มไฟล์เสียงไปยังงานนำเสนอจากสตรีม. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | สร้างและเพิ่มไฟล์เสียงไปยังงานนำเสนอจากสตรีม. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | สร้างและเพิ่มไฟล์เสียงไปยังงานนำเสนอจากอาร์เรย์ไบต์. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกไฟล์เสียงไปยังอาร์เรย์ที่ระบุเริ่มจากตำแหน่งที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | ส่งคืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันนี้เป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด). |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืนรากของการซิงโครไนซ์. |
| [iterator()](#iterator--) | ส่งคืน enumerator ที่วนซ้ำผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด. |
### size() {#size--}
```
public final int size()
```


ส่งคืนจำนวนไฟล์เสียงในคอลเลกชัน. อ่านอย่างเดียว int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```


รับอิลิเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IAudio](../../com.aspose.slides/iaudio).

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```


เพิ่มสำเนาของไฟล์เสียงจากงานนำเสนออื่น.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | ไฟล์เสียงต้นทาง. |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio) - ไฟล์เสียงที่เพิ่ม.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```


สร้างและเพิ่มไฟล์เสียงไปยังงานนำเสนอจากสตรีม.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมเพื่อเพิ่มไฟล์เสียงจาก. |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio) - ไฟล์เสียงที่เพิ่ม.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


สร้างและเพิ่มไฟล์เสียงไปยังงานนำเสนอจากสตรีม.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมเพื่อเพิ่มไฟล์เสียงจากวิดีโอ. |
| loadingStreamBehavior | int | พฤติกรรมที่จะถูกนำไปใช้กับสตรีม. |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio) - ไฟล์เสียงที่เพิ่ม.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```


สร้างและเพิ่มไฟล์เสียงไปยังงานนำเสนอจากอาร์เรย์ไบต์.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| audioData | byte[] | ไบต์ของไฟล์เสียง. |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio) - ไฟล์เสียงที่เพิ่ม.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


คัดลอกไฟล์เสียงไปยังอาร์เรย์ที่ระบุเริ่มจากตำแหน่งที่ระบุ.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์. |
| index | int | ดัชนี. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


ส่งคืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันนี้เป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


ส่งคืนรากของการซิงโครไนซ์. อ่านอย่างเดียว Object.

**Returns:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```


ส่งคืน enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - IGenericEnumerator ที่สามารถใช้วนซ้ำผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```


ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด