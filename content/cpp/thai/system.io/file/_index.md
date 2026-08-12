---
title: File
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ให้เมธอดสำหรับการจัดการไฟล์ ประเภทนี้เป็นแบบสแตติกโดยไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใดๆ
type: docs
weight: 261
url: /th/system.io/file/
---
## คลาส File

ให้เมธอดสำหรับการจัดการไฟล์ ประเภทนี้เป็นแบบสแตติกโดยไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใดๆ

```cpp
class File
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | เพิ่มสตริงจากคอลเลกชันของสตริงที่ระบุไปยังไฟล์ที่ระบุโดยใช้การเข้ารหัสที่ระบุ โดยเขียนแต่ละสตริงในบรรทัดใหม่ หากไฟล์ที่ระบุไม่มีอยู่ จะถูกสร้างขึ้น ไฟล์จะถูกปิดหลังจากเขียนสตริงทั้งหมดแล้ว |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | เพิ่มสตริงที่ระบุไปยังไฟล์ที่ระบุโดยใช้การเข้ารหัสที่ระบุ |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | สร้างวัตถุ [StreamWriter](../streamwriter/) ที่เพิ่มข้อความไปยังไฟล์ที่ระบุโดยใช้การเข้ารหัส UTF-8 หากไฟล์ที่ระบุไม่มีอยู่ จะถูกสร้างขึ้น |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | คัดลอกไฟล์ที่ระบุไปยังตำแหน่งที่ระบุ หากไฟล์ปลายทางมีอยู่แล้ว พารามิเตอร์หนึ่งจะระบุว่าจะเขียนทับหรือไม่ |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | สร้างไฟล์ใหม่ (หรือเขียนทับไฟล์ที่มีอยู่) และเปิดเพื่อการอ่านและเขียนโดยใช้ขนาดบัฟเฟอร์และตัวเลือกที่ระบุ |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | สร้างไฟล์ใหม่หรือเปิดไฟล์ที่มีอยู่เพื่อเขียนข้อความที่เข้ารหัสเป็น UTF-8 |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | ยังไม่ได้ดำเนินการ |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | ลบไฟล์หรือไดเรกทอรีที่ระบุ |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | ยังไม่ได้ดำเนินการ |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | ตรวจสอบว่าพาธที่ระบุอ้างอิงถึงไฟล์ที่มีอยู่หรือไม่ |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | คืนค่าแอตทริบิวต์ของเอนทิตีที่ระบุ |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | คืนค่าเวลาการสร้างของเอนทิตีที่ระบุในรูปแบบเวลาท้องถิ่น |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | คืนค่าเวลาการสร้างของเอนทิตีที่ระบุในรูปแบบเวลา UTC |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | คืนค่าเวลาการเข้าถึงล่าสุดของเอนทิตีที่ระบุในรูปแบบเวลาท้องถิ่น |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | คืนค่าเวลาการเข้าถึงล่าสุดของเอนทิตีที่ระบุในรูปแบบเวลา UTC |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | คืนค่าเวลาการเขียนล่าสุดของเอนทิตีที่ระบุในรูปแบบเวลาท้องถิ่น |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | คืนค่าเวลาการเขียนล่าสุดของเอนทิตีที่ระบุในรูปแบบเวลา UTC |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ย้ายไฟล์ที่ระบุไปยังตำแหน่งใหม่ |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | เปิดไฟล์ที่ระบุในโหมดที่ระบุสำหรับการอ่านและเขียนโดยไม่มีการแชร์ |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | เปิดไฟล์ที่ระบุในโหมดที่ระบุ พร้อมประเภทการเข้าถึงและตัวเลือกการแชร์ที่ระบุ |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | เปิดไฟล์ที่ระบุเพื่ออ่านอย่างเดียวในโหมด 'Open' พร้อมการเข้าถึงแบบแชร์สำหรับการอ่าน |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | เปิดไฟล์ที่มีอยู่แล้วเพื่ออ่านข้อความโดยใช้การเข้ารหัส UTF-8 โดยไม่มีการแชร์ |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | เปิดไฟล์ที่ระบุเพื่อเขียนอย่างเดียวในโหมด 'OpenOrCreate' โดยไม่มีการแชร์ |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | อ่านเนื้อหาของไฟล์ไบนารีที่ระบุไปยังอาร์เรย์ไบต์ |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | อ่านเนื้อหาของไฟล์ข้อความที่ระบุบรรทัดต่อบรรทัดไปยังอาร์เรย์ของสตริงโดยใช้การเข้ารหัสอักขระที่ระบุ |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | อ่านเนื้อหาของไฟล์ข้อความที่ระบุไปยังวัตถุ [String](../../system/string/) เดียวโดยใช้การเข้ารหัสอักขระที่ระบุ |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | อ่านเนื้อหาของไฟล์ข้อความที่ระบุบรรทัดต่อบรรทัดโดยใช้การเข้ารหัสอักขระที่ระบุและคืนค่าคอลเลกชันของสตริงที่แสดงถึงบรรทัดเดียวของเนื้อหาไฟล์ |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | แทนที่เนื้อหาของไฟล์หนึ่งด้วยไฟล์อื่นและสร้างสำเนาสำรองของไฟล์ที่ถูกแทนที่ |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | ตั้งค่าแอตทริบิวต์ที่ระบุบนไฟล์ที่ระบุ |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | ยังไม่ได้ดำเนินการ |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | ยังไม่ได้ดำเนินการ |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | ยังไม่ได้ดำเนินการ |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | ยังไม่ได้ดำเนินการ |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | ตั้งค่าเวลาการเขียนล่าสุดของเอนทิตีที่ระบุเป็นเวลาท้องถิ่น |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | ตั้งค่าเวลาการเขียนล่าสุดของเอนทิตีที่ระบุเป็นเวลา UTC |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | เขียนทับไฟล์ไบนารีที่ระบุและเขียนไบต์ที่ระบุลงไป |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | สร้างไฟล์ข้อความใหม่หรือเขียนทับไฟล์ที่มีอยู่และเขียนสตริงทั้งหมดจากคอลเลกชันของสตริงที่ระบุต่อกันไปยังไฟล์นั้น โดยแต่ละสตริงอยู่ในบรรทัดใหม่ โดยใช้การเข้ารหัสที่ระบุ |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | สร้างไฟล์ข้อความใหม่หรือเขียนทับไฟล์ที่มีอยู่และเขียนสตริงทั้งหมดจากอาร์เรย์ของสตริงที่ระบุไปยังไฟล์นั้น โดยแต่ละสตริงอยู่ในบรรทัดใหม่ โดยใช้การเข้ารหัสที่ระบุ |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | สร้างไฟล์ข้อความใหม่หรือเขียนทับไฟล์ที่มีอยู่และเขียนเนื้อหาของสตริงที่ระบุไปยังไฟล์นั้นโดยใช้การเข้ารหัสที่ระบุ |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | ค่าตั้งต้นของจำนวนไบต์ที่บัฟเฟอร์ระหว่างการอ่านและเขียนไฟล์ |

## ดูเพิ่มเติม

* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)