---
title: IAudioCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงคอลเลกชันของไฟล์เสียงที่ฝังอยู่
type: docs
url: /th/com.aspose.slides/iaudiocollection/
---
**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

เป็นคอลเลกชันของไฟล์เสียงที่ฝังอยู่
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | เพิ่มสำเนาของไฟล์เสียงจากการนำเสนออื่น. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | สร้างและเพิ่มไฟล์เสียงลงในการนำเสนอจากสตรีม. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | สร้างและเพิ่มไฟล์เสียงลงในการนำเสนอจากสตรีม. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | สร้างและเพิ่มไฟล์เสียงลงในการนำเสนอจากอาร์เรย์ของไบต์. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```

ดึงองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IAudio](../../com.aspose.slides/iaudio).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```

เพิ่มสำเนาของไฟล์เสียงจากการนำเสนออื่น.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | ไฟล์เสียงต้นทาง. |

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio) - เสียงที่เพิ่ม
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

สร้างและเพิ่มไฟล์เสียงลงในการนำเสนอจากสตรีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมสำหรับเพิ่มไฟล์เสียง. |

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio) - เสียงที่เพิ่ม
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

สร้างและเพิ่มไฟล์เสียงลงในการนำเสนอจากสตรีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมสำหรับเพิ่มไฟล์เสียง. |
| loadingStreamBehavior | int | [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) ที่จะใช้กับสตรีม. |

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio) - เสียงที่เพิ่ม
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

สร้างและเพิ่มไฟล์เสียงลงในการนำเสนอจากอาร์เรย์ของไบต์.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| audioData | byte[] | ไบต์ของไฟล์เสียง. |

**ผลลัพธ์:**
[IAudio](../../com.aspose.slides/iaudio) - เสียงที่เพิ่ม