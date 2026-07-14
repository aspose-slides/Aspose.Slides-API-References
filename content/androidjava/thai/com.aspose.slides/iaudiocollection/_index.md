---
title: IAudioCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: เป็นคอลเลกชันของไฟล์เสียงที่ฝังไว้
type: docs
url: /th/com.aspose.slides/iaudiocollection/
---
**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

เป็นคอลเลกชันของไฟล์เสียงที่ฝังไว้
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงอิลีเมนต์ที่ตำแหน่งที่ระบุ. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | เพิ่มสำเนาของไฟล์เสียงจากงานนำเสนออื่น. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | สร้างและเพิ่มไฟล์เสียงลงในงานนำเสนอจากสตรีม. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | สร้างและเพิ่มไฟล์เสียงลงในงานนำเสนอจากสตรีม. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | สร้างและเพิ่มไฟล์เสียงลงในงานนำเสนอจากอาร์เรย์ไบต์. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```

ดึงอิลีเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IAudio](../../com.aspose.slides/iaudio).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```

เพิ่มสำเนาของไฟล์เสียงจากงานนำเสนออื่น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | ไฟล์เสียงต้นทาง. |

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio) - ไฟล์เสียงที่เพิ่ม.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

สร้างและเพิ่มไฟล์เสียงลงในงานนำเสนอจากสตรีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมที่จะเพิ่มไฟล์เสียงจาก. |

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio) - ไฟล์เสียงที่เพิ่ม.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

สร้างและเพิ่มไฟล์เสียงลงในงานนำเสนอจากสตรีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมเพื่อเพิ่มวิดีโอและเสียงจาก. |
| loadingStreamBehavior | int | [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) ที่จะนำไปใช้กับสตรีม. |

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio) - ไฟล์เสียงที่เพิ่ม.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

สร้างและเพิ่มไฟล์เสียงลงในงานนำเสนอจากอาร์เรย์ไบต์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| audioData | byte[] | ไบต์ของไฟล์เสียง. |

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio) - ไฟล์เสียงที่เพิ่ม.