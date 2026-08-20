---
title: AudioCollection
second_title: Aspose.Slides สำหรับเอกสารอ้างอิง API ของ Java
description: เป็นคอลเลกชันของไฟล์เสียงที่ฝังอยู่.
type: docs
url: /th/com.aspose.slides/audiocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Represents a collection of embedded audio files.
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [size()](#size--) | คืนค่าจำนวนไฟล์เสียงในคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | รับอีลเมนต์ที่ตำแหน่งที่ระบุ. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | เพิ่มสำเนาของไฟล์เสียงจากงานนำเสนออื่น. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | สร้างและเพิ่มไฟล์เสียงลงในงานนำเสนอจากสตรีม. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | สร้างและเพิ่มไฟล์เสียงลงในงานนำเสนอจากสตรีม. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | สร้างและเพิ่มไฟล์เสียงลงในงานนำเสนอจากอาร์เรย์ไบต์. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกไฟล์เสียงไปยังอาร์เรย์ที่ระบุเริ่มจากตำแหน่งที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | คืนค่าซึ่งบ่งชี้ว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | คืนค่าฐานการซิงโครไนซ์. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
### size() {#size--}
```
public final int size()
```


คืนค่าจำนวนไฟล์เสียงในคอลเลกชัน. อ่านได้อย่างเดียว int.

**ผลลัพธ์:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```


รับอีลเมนต์ที่ตำแหน่งที่ระบุ. อ่านได้อย่างเดียว [IAudio](../../com.aspose.slides/iaudio).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```


เพิ่มสำเนาของไฟล์เสียงจากงานนำเสนออื่น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | ไฟล์เสียงต้นฉบับ. |

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio) - ไฟล์เสียงที่เพิ่ม
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```


สร้างและเพิ่มไฟล์เสียงลงในงานนำเสนอจากสตรีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมสำหรับเพิ่มไฟล์เสียง. |

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio) - ไฟล์เสียงที่เพิ่ม
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


สร้างและเพิ่มไฟล์เสียงลงในงานนำเสนอจากสตรีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมสำหรับเพิ่มไฟล์เสียงวิดีโอ. |
| loadingStreamBehavior | int | พฤติกรรมที่จะนำไปใช้กับสตรีม. |

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio) - ไฟล์เสียงที่เพิ่ม
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```


สร้างและเพิ่มไฟล์เสียงลงในงานนำเสนอจากอาร์เรย์ไบต์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| audioData | byte[] | ไบต์ของไฟล์เสียง. |

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio) - ไฟล์เสียงที่เพิ่ม
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


คัดลอกไฟล์เสียงไปยังอาร์เรย์ที่ระบุเริ่มจากตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์. |
| index | int | ตำแหน่ง. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


คืนค่าซึ่งบ่งชี้ว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (thread-safe). อ่านได้อย่างเดียว boolean.

**ผลลัพธ์:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


คืนค่าฐานการซิงโครไนซ์. อ่านได้อย่างเดียว Object.

**ผลลัพธ์:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```


คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```


คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - An java.util.Iterator for the entire collection.