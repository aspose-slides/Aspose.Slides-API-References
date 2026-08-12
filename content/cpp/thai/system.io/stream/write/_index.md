---
title: Write()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: เขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่กำหนดไปยังสตรีม.
type: docs
weight: 53
url: /th/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด

เขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่กำหนดไปยังสตรีม

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ที่บรรจุไบต์ที่จะเขียน |
| offset | **int32_t** | ดัชนีเริ่มต้นที่ 0 ขององค์ประกอบใน **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | **int32_t** | จำนวนขององค์ประกอบในช่วงย่อยที่จะเขียน |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) เมธอด

เขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่กำหนดไปยังสตรีม

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | มุมมองอาร์เรย์ที่บรรจุไบต์ที่จะเขียน |
| offset | **int32_t** | ดัชนีเริ่มต้นที่ 0 ขององค์ประกอบใน **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | **int32_t** | จำนวนขององค์ประกอบในช่วงย่อยที่จะเขียน |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) เมธอด

เขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่กำหนดไปยังสตรีม

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| N | ขนาดของอาร์เรย์แบบสแตก |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | อาร์เรย์แบบสแตกที่บรรจุไบต์ที่จะเขียน |
| offset | **int32_t** | ดัชนีเริ่มต้นที่ 0 ขององค์ประกอบใน **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | **int32_t** | จำนวนขององค์ประกอบในช่วงย่อยที่จะเขียน |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) เมธอด

เขียนช่วงย่อยของไบต์ที่ระบุจากช่วงไบต์ที่กำหนดไปยังสตรีม

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | ช่วงไบต์ที่จะอ่านไบต์ที่เขียนจาก |

## ดูเพิ่มเติม

* ไทป์เดฟ [ArrayPtr](../../../system/arrayptr/)
* คลาส [Stream](../)
* คลาส [ReadOnlySpan](../../../system/readonlyspan/)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)