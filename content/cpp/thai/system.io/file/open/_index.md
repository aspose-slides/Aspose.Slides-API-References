---
title: Open()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: เปิดไฟล์ที่ระบุในโหมดที่กำหนดเพื่อการอ่านและเขียนโดยไม่มีการแชร์
type: docs
weight: 235
url: /th/system.io/file/open/
---
## File::Open(const String&, FileMode) เมธอด


เปิดไฟล์ที่ระบุในโหมดที่กำหนดสำหรับการอ่านและเขียนโดยไม่มีการแชร์

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | เส้นทางของไฟล์ที่ต้องการเปิด |
| mode | [FileMode](../../filemode/) | ระบุโหมดที่ใช้เปิดไฟล์ |

### Return Value

วัตถุ [FileStream](../../filestream/) ที่เชื่อมโยงกับไฟล์ที่เปิด

## File::Open(const String&, FileMode, FileAccess, FileShare) เมธอด


เปิดไฟล์ที่ระบุในโหมดที่กำหนด พร้อมประเภทการเข้าถึงและตัวเลือกการแชร์ที่กำหนด

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | เส้นทางของไฟล์ที่ต้องการเปิด |
| mode | [FileMode](../../filemode/) | ระบุโหมดที่ใช้เปิดไฟล์ |
| access | [FileAccess](../../fileaccess/) | ประเภทการเข้าถึงที่ร้องขอ |
| share | [FileShare](../../fileshare/) | ประเภทการเข้าถึงที่วัตถุ [FileStream](../../filestream/) อื่นมีต่อไฟล์ที่เปิด |

### Return Value

วัตถุ [FileStream](../../filestream/) ที่เชื่อมโยงกับไฟล์ที่เปิด

## ดูเพิ่มเติม

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)