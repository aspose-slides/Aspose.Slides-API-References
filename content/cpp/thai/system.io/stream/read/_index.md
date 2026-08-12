---
title: Read()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาร์เรย์ไบต์ที่ระบุ
type: docs
weight: 27
url: /th/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด


อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาร์เรย์ไบต์ที่ระบุ

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ไบต์สำหรับเขียนไบต์ที่อ่าน |
| offset | **int32_t** | ตำแหน่งเริ่มต้นที่นับจาก 0 ใน **buffer** เพื่อเริ่มเขียน |
| count | **int32_t** | จำนวนไบต์ที่ต้องการอ่าน |

### ค่าที่คืนกลับ

จำนวนไบต์ที่อ่าน

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) เมธอด


อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาร์เรย์ไบต์ที่ระบุ

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | มุมมองอาร์เรย์ไบต์สำหรับเขียนไบต์ที่อ่าน |
| offset | **int32_t** | ตำแหน่งเริ่มต้นที่นับจาก 0 ใน **buffer** เพื่อเริ่มเขียน |
| count | **int32_t** | จำนวนไบต์ที่ต้องการอ่าน |

### ค่าที่คืนกลับ

จำนวนไบต์ที่อ่าน

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) เมธอด


อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาร์เรย์ไบต์ที่ระบุ

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| N | ขนาดของสแตกอาร์เรย์ |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | อาร์เรย์สแตกไบต์สำหรับเขียนไบต์ที่อ่าน |
| offset | **int32_t** | ตำแหน่งเริ่มต้นที่นับจาก 0 ใน **buffer** เพื่อเริ่มเขียน |
| count | **int32_t** | จำนวนไบต์ที่ต้องการอ่าน |

### ค่าที่คืนกลับ

จำนวนไบต์ที่อ่าน

## Stream::Read(const System::Span\<uint8_t\>\&) เมธอด


อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในช่วงไบต์ที่ระบุ

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | ช่วงไบต์สำหรับเขียนไบต์ที่อ่าน |

### ค่าที่คืนกลับ

จำนวนไบต์ที่อ่าน

## ดูเพิ่มเติม

* กำหนดชนิด [ArrayPtr](../../../system/arrayptr/)
* คลาส [Stream](../)
* คลาส [Span](../../../system/span/)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)