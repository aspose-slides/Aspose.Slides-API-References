---
title: FileStream()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอินสแตนซ์ใหม่ของคลาส FileStream และกำหนดค่าเริ่มต้นด้วยพารามิเตอร์ที่ระบุ
type: docs
weight: 1
url: /th/system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) constructor


สร้างอินสแตนซ์ใหม่ของคลาส [FileStream](../) และกำหนดค่าเริ่มต้นด้วยพารามิเตอร์ที่ระบุ

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | เส้นทางของไฟล์ที่จะเปิด |
| mode | [FileMode](../../filemode/) | ระบุโหมดที่ใช้เปิดไฟล์ |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) constructor


สร้างอินสแตนซ์ใหม่ของคลาส [FileStream](../) และกำหนดค่าเริ่มต้นด้วยพารามิเตอร์ที่ระบุ

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | เส้นทางของไฟล์ที่จะเปิด |
| mode | [FileMode](../../filemode/) | ระบุโหมดที่ใช้เปิดไฟล์ |
| access | [FileAccess](../../fileaccess/) | ประเภทการเข้าถึงที่ร้องขอ |
| share | [FileShare](../../fileshare/) | ประเภทการเข้าถึงที่วัตถุ [FileStream](../) อื่น ๆ มีต่อไฟล์ที่เปิด |
| buffer_size | **int32_t** | จำนวนไบต์ที่บัฟเฟอร์ระหว่างการอ่านและเขียน |
| options | [FileOptions](../../fileoptions/) | ตัวเลือกเพิ่มเติม |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) constructor


สร้างอินสแตนซ์ใหม่ของคลาส [FileStream](../) และกำหนดค่าเริ่มต้นด้วยพารามิเตอร์ที่ระบุ

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | เส้นทางของไฟล์ที่จะเปิด |
| mode | [FileMode](../../filemode/) | ระบุโหมดที่ใช้เปิดไฟล์ |
| access | [FileAccess](../../fileaccess/) | ประเภทการเข้าถึงที่ร้องขอ |
| share | [FileShare](../../fileshare/) | ประเภทการเข้าถึงที่วัตถุ [FileStream](../) อื่น ๆ มีต่อไฟล์ที่เปิด |
| buffer_size | **int32_t** | จำนวนไบต์ที่บัฟเฟอร์ระหว่างการอ่านและเขียน |
| useAsync | **bool** | ระบุว่าจะใช้ I/O แบบอะซิงโครนัสหรือซิงโครนัส |

## หมายเหตุ



ระบบปฏิบัติการพื้นฐานอาจไม่รองรับ I/O แบบอะซิงโครนัส. 

## FileStream::FileStream(const FileStream\&) constructor




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## ดูเพิ่มเติม

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Class [String](../../../system/string/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)