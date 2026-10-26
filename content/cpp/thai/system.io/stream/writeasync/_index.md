---
title: WriteAsync()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เขียนลำดับของไบต์ไปยังสตรีมปัจจุบันแบบไม่บล็อก, เลื่อนตำแหน่งปัจจุบันในสตรีมนี้ตามจำนวนไบต์ที่เขียน, และตรวจสอบคำขอยกเลิก
type: docs
weight: 66
url: /th/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) เมธอด


Asynchronously writes a sequence of bytes to the current stream, advances the current position within this stream by the number of bytes written, and monitors cancellation requests.

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ที่บรรจุไบต์ที่จะเขียน |
| offset | **int32_t** | ดัชนีเริ่มต้นที่ 0 ขององค์ประกอบใน **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | **int32_t** | จำนวนองค์ประกอบในช่วงย่อยที่จะเขียน |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | โทเค็นที่ใช้ตรวจสอบคำขอยกเลิก |

### ค่าที่คืน

A task that represents the asynchronous write operation.

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด


Asynchronously writes a sequence of bytes to the current stream, advances the current position within this stream by the number of bytes written, and monitors cancellation requests.

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ที่บรรจุไบต์ที่จะเขียน |
| offset | **int32_t** | ดัชนีเริ่มต้นที่ 0 ขององค์ประกอบใน **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | **int32_t** | จำนวนองค์ประกอบในช่วงย่อยที่จะเขียน |

### ค่าที่คืน

A task that represents the asynchronous write operation.

## ดูเพิ่มเติม

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)