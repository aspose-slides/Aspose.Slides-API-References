---
title: Open()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เปิดไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันในโหมดที่ระบุสำหรับการอ่านและการเขียนโดยไม่มีการแชร์
type: docs
weight: 183
url: /th/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) เมธอด

เปิดไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันในโหมดที่ระบุสำหรับการอ่านและการเขียนและไม่มีการแชร์

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | ระบุโหมดที่ใช้เปิดไฟล์ |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [FileStream](../../filestream/) ที่เกี่ยวข้องกับไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน

## FileInfo::Open(FileMode, FileAccess) เมธอด

เปิดไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันในโหมดที่ระบุ โดยมีประเภทการเข้าถึงที่ระบุและไม่มีการแชร์

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | ระบุโหมดที่ใช้เปิดไฟล์ |
| access | [FileAccess](../../fileaccess/) | ประเภทการเข้าถึงที่ร้องขอ |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [FileStream](../../filestream/) ที่เกี่ยวข้องกับไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน

## FileInfo::Open(FileMode, FileAccess, FileShare) เมธอด

เปิดไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันในโหมดที่ระบุ โดยมีประเภทการเข้าถึงและตัวเลือกการแชร์ที่ระบุ

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | ระบุโหมดที่ใช้เปิดไฟล์ |
| access | [FileAccess](../../fileaccess/) | ประเภทการเข้าถึงที่ร้องขอ |
| share | [FileShare](../../fileshare/) | ประเภทของการเข้าถึงที่อ็อบเจ็กต์ [FileStream](../../filestream/) อื่น ๆ มีต่อไฟล์ที่เปิด |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [FileStream](../../filestream/) ที่เกี่ยวข้องกับไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน

## ดูเพิ่มเติม

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)