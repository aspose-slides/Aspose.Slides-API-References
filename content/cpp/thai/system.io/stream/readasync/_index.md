---
title: ReadAsync()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: อ่านลำดับของไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนตำแหน่งภายในสตรีมตามจำนวนไบต์ที่อ่าน, และตรวจสอบคำขอยกเลิก
type: docs
weight: 40
url: /th/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) เมธอด

อ่านลำดับของไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนตำแหน่งภายในสตรีมตามจำนวนไบต์ที่อ่าน, และตรวจสอบคำขอยกเลิก

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ไบต์เพื่อเขียนไบต์ที่อ่านลงไป |
| offset | **int32_t** | ตำแหน่งที่เริ่มจาก 0 ใน **buffer** เพื่อเริ่มเขียนที่ |
| count | **int32_t** | จำนวนไบต์ที่จะอ่าน |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | โทเคนสำหรับตรวจสอบคำขอยกเลิก |

### ค่าที่คืน

งานที่แสดงถึงการดำเนินการอ่านแบบอะซิงโครนัส ค่า parameter TResult จะมีจำนวนไบต์ทั้งหมดที่อ่านเข้าไปใน buffer ค่ารีเทิร์นอาจน้อยกว่าจำนวนไบต์ที่ร้องขอได้ หากจำนวนไบต์ที่มีอยู่ในขณะนั้นน้อยกว่าจำนวนที่ต้องการ, หรืออาจเป็น 0 (ศูนย์) หากถึงจุดสิ้นสุดของสตรีมแล้ว

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด

อ่านลำดับของไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนตำแหน่งภายในสตรีมตามจำนวนไบต์ที่อ่าน, และตรวจสอบคำขอยกเลิก

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ไบต์เพื่อเขียนไบต์ที่อ่านลงไป |
| offset | **int32_t** | ตำแหน่งที่เริ่มจาก 0 ใน **buffer** เพื่อเริ่มเขียนที่ |
| count | **int32_t** | จำนวนไบต์ที่จะอ่าน |

### ค่าที่คืน

งานที่แสดงถึงการดำเนินการอ่านแบบอะซิงโครนัส ค่า parameter TResult จะมีจำนวนไบต์ทั้งหมดที่อ่านเข้าไปใน buffer ค่ารีเทิร์นอาจน้อยกว่าจำนวนไบต์ที่ร้องขอได้ หากจำนวนไบต์ที่มีอยู่ในขณะนั้นน้อยกว่าจำนวนที่ต้องการ, หรืออาจเป็น 0 (ศูนย์) หากถึงจุดสิ้นสุดของสตรีมแล้ว

## ดูเพิ่มเติม

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [CancellationToken](../../../system.threading/cancellationtoken/)
* คลาส [Stream](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)