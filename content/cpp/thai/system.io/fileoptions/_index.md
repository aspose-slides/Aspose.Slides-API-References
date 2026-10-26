---
title: FileOptions
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงตัวเลือกขั้นสูงสำหรับการสร้างอ็อบเจกต์ FileStream
type: docs
weight: 521
url: /th/system.io/fileoptions/
---
## FileOptions enum

แสดงถึงตัวเลือกขั้นสูงสำหรับการสร้างวัตถุ [FileStream](../filestream/).

```cpp
enum class FileOptions
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| None | 0 | ไม่มีตัวเลือกเพิ่มเติม |
| Encrypted | 16384 | ไฟล์ถูกเข้ารหัส. NOT IMPLEMENTED. |
| DeleteOnClose | 67108864 | ไฟล์ควรถูกลบโดยอัตโนมัติเมื่อไม่ถูกใช้งานอีกต่อไป |
| SequentialScan | 134217728 | ไฟล์ควรเข้าถึงแบบต่อเนื่อง |
| RandomAccess | 268435456 | ไฟล์ถูกเข้าถึงแบบสุ่ม |
| Asynchronous | 1073741824 | ไฟล์สามารถใช้ในการทำงาน I/O แบบอะซิงโครนัสได้ |
| WriteThrough | n/a | การเขียนทั้งหมดควรส่งตรงไปยังดิสก์โดยข้ามแคชกลาง |

## ดูเพิ่มเติม

* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)