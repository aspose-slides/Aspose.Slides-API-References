---
title: Write()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: หากโหมดการห่อหุ้มเป็นแบบไบนารี จะเขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุลงในสตรีม มิฉะนั้นจะเปลี่ยนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุเป็นประเภท char_type แล้วเขียนผลลัพธ์ลงในสตรีม
type: docs
weight: 79
url: /th/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด

หากโหมดการห่อหุ้มเป็นแบบไบนารี จะเขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุลงในสตรีม มิฉะนั้นจะเปลี่ยนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุเป็นประเภท char_type แล้วเขียนผลลัพธ์ลงในสตรีม。

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ที่บรรจุไบต์ที่ต้องการเขียน |
| offset | **int32_t** | ดัชนีเริ่มต้นที่ 0 ขององค์ประกอบใน **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | **int32_t** | จำนวนองค์ประกอบในช่วงย่อยที่ต้องการเขียน |

## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) เมธอด

เขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุลงในสตรีม。

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | มุมมองอาร์เรย์ที่บรรจุไบต์ที่ต้องการเขียน |
| offset | **int32_t** | ดัชนีเริ่มต้นที่ 0 ขององค์ประกอบใน **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | **int32_t** | จำนวนองค์ประกอบในช่วงย่อยที่ต้องการเขียน |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [BasicSTDOStreamWrapper](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)