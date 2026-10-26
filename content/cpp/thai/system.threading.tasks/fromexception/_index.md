---
title: FromException()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: สร้างงานที่เสร็จสิ้นพร้อมกับข้อยกเว้นที่ระบุ
type: docs
weight: 131
url: /th/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) ฟังก์ชัน

สร้างงานที่เสร็จสิ้นพร้อมกับข้อยกเว้นที่ระบุ

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | ข้อยกเว้นที่จะใช้ในการทำให้งานเสร็จสิ้น |

### ค่าที่ส่งกลับ

งานที่ล้มเหลว

## System::Threading::Tasks::FromException(const Exception\&) ฟังก์ชัน

สร้างงานที่เสร็จสิ้นพร้อมกับข้อยกเว้นที่ระบุและประเภทผลลัพธ์

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TResult | ประเภทของผลลัพธ์ของงาน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | ข้อยกเว้นที่จะใช้ในการทำให้งานเสร็จสิ้น |

### ค่าที่ส่งกลับ

งานที่ล้มเหลวพร้อมกับประเภทผลลัพธ์ที่ระบุ

## ดูเพิ่มเติม

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* เนมสเปซ [System::Threading::Tasks](../)
* ไลบรารี [Aspose.Slides](../../)