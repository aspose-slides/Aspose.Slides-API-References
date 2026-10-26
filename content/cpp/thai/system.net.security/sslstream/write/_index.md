---
title: Write()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เขียนอาร์เรย์ไบต์ที่ระบุไปยังสตรีม.
type: docs
weight: 404
url: /th/system.net.security/sslstream/write/
---
## SslStream::Write(const ArrayPtr\<uint8_t\>\&) method


เขียนอาร์เรย์ไบต์ที่ระบุไปยังสตรีม。

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ไบต์ที่จะเขียน। |

## SslStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


เขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุไปยังสตรีม。

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ที่บรรจุไบต์ที่จะเขียน |
| offset | **int32_t** | ดัชนีที่เริ่มจาก 0 ขององค์ประกอบใน **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | **int32_t** | จำนวนองค์ประกอบในช่วงย่อยที่จะเขียน |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&) method


เขียนอาร์เรย์ไบต์ที่ระบุไปยังสตรีม。

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | อาร์เรย์ไบต์ที่จะเขียน。 |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


เขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุไปยังสตรีม。

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | อาร์เรย์ที่บรรจุไบต์ที่จะเขียน |
| offset | **int32_t** | ดัชนีที่เริ่มจาก 0 ขององค์ประกอบใน **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | **int32_t** | จำนวนองค์ประกอบในช่วงย่อยที่จะเขียน |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [SslStream](../)
* เนมสเปซ [System::Net::Security](../../)
* ไลบรารี [Aspose.Slides](../../../)