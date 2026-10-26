---
title: ReadAsync()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: อ่านลำดับไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนตำแหน่งภายในสตรีมตามจำนวนไบต์ที่อ่าน, และตรวจสอบคำขอยกเลิก
type: docs
weight: 196
url: /th/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) เมธอด

อ่านลำดับไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนตำแหน่งภายในสตรีมตามจำนวนไบต์ที่อ่าน, และตรวจสอบคำขอยกเลิก

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาเรย์ไบต์เพื่อเขียนไบต์ที่อ่านได้ |
| offset | **int32_t** | ตำแหน่งเริ่มต้นแบบ 0-based ใน **buffer** เพื่อเริ่มเขียน |
| count | **int32_t** | จำนวนไบต์ที่จะอ่าน |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | โทเค็นสำหรับตรวจสอบคำขอยกเลิก |

### ค่า คืนค่า

งาน (task) ที่แทนการดำเนินการอ่านแบบอะซิงโครนัส ค่า параметра TResult มีจำนวนไบต์ทั้งหมดที่อ่านเข้ามาในบัฟเฟอร์ ค่าอาจน้อยกว่าจำนวนไบต์ที่ร้องขอได้หากจำนวนไบต์ที่มีอยู่ในขณะนั้นน้อยกว่าที่ร้องขอ, หรืออาจเป็น 0 (ศูนย์) หากถึงจุดสิ้นสุดของสตรีม

## ดูเพิ่ม

* แบบกำหนดชนิด [RTaskPtr](../../../system/rtaskptr/)
* แบบกำหนดชนิด [ArrayPtr](../../../system/arrayptr/)
* คลาส [CancellationToken](../../../system.threading/cancellationtoken/)
* คลาส [FileStream](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)