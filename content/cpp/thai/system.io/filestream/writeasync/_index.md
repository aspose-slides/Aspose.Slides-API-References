---
title: WriteAsync()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เขียนลำดับของไบต์ไปยังสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนตำแหน่งปัจจุบันภายในสตรีมตามจำนวนไบต์ที่เขียน, และตรวจสอบคำขอยกเลิก
type: docs
weight: 261
url: /th/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method

เขียนลำดับของไบต์ไปยังสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนตำแหน่งปัจจุบันภายในสตรีมตามจำนวนไบต์ที่เขียน, และตรวจสอบคำขอยกเลิก

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาเรย์ที่มีไบต์ที่จะเขียน |
| offset | **int32_t** | ดัชนีเริ่มจาก 0 ขององค์ประกอบใน **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | **int32_t** | จำนวนองค์ประกอบในช่วงย่อยที่จะเขียน |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | โทเค็นที่ใช้ตรวจสอบคำขอยกเลิก |

### ค่าที่ส่งกลับ

งานที่แทนการดำเนินการเขียนแบบอะซิงโครนัส

## ดูเพิ่มเติม

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)