---
title: BindingFlags
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดสมาชิกและโหมดการค้นหาประเภทและการผูก
type: docs
weight: 157
url: /th/system.reflection/bindingflags/
---
## BindingFlags enum

กำหนดสมาชิกและโหมดการค้นหาประเภทและการผูก

```cpp
enum class BindingFlags
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| Default | 0 | ไม่มีตัวเลือกพิเศษ |
| IgnoreCase | 1 | ละเว้นตัวพิมพ์ใหญ่/เล็กของชื่อเมื่อค้นหารายการ |
| DeclaredOnly | 2 | ค้นหาเฉพาะสมาชิกที่ประกาศในประเภทและไม่รวมในประเภทฐาน |
| Instance | 4 | ค้นหาผ่านสมาชิกอินสแตนซ์ |
| Static | 8 | ค้นหาผ่านสมาชิก static |
| Public | 16 | ค้นหาผ่านสมาชิกสาธารณะ |
| NonPublic | 32 | ค้นหาผ่านสมาชิกที่ไม่สาธารณะ |
| FlattenHierarchy | 64 | ค้นหาผ่านสมาชิก static สาธารณะและที่ป้องกันของประเภทฐาน |
| InvokeMethod | 256 | เรียกใช้เมธอด |
| CreateInstance | 512 | สร้างอินสแตนซ์ของประเภทที่สะท้อน |
| GetField | 1024 | ดึงค่าฟิลด์ |
| SetField | 2048 | ตั้งค่าฟิลด์ |
| GetProperty | 4096 | ดึงค่าคุณสมบัติ |
| SetProperty | 8192 | ตั้งค่าคุณสมบัติ |
| PutDispProperty | 16384 | ใส่คุณสมบัติ COM |
| PutRefDispProperty | 32768 | ใส่คุณสมบัติอ้างอิง COM |
| ExactBinding | 65536 | การผูกประเภทต้องตรงอย่างสมบูรณ์โดยไม่มีการเปลี่ยนแปลงประเภท |
| SuppressChangeType | 131072 | ไม่รองรับ |
| OptionalParamBinding | 262144 | เลือกการโอเวอร์โหลดตามจำนวนอากูเมนต์ |
| IgnoreReturn | 16777216 | ละเว้นค่าที่ส่งกลับจาก COM interop |

## ดูเพิ่มเติม

* เนมสเปซ [System::Reflection](../)
* ไลบรารี [Aspose.Slides](../../)