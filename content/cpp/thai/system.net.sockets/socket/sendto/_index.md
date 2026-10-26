---
title: SendTo()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ส่งข้อมูลที่ระบุไปยังจุดสิ้นสุดที่ระบุ
type: docs
weight: 651
url: /th/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) เมธอด

ส่งข้อมูลที่ระบุไปยังจุดสิ้นสุดที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ข้อมูลที่จะส่ง |
| offset | **int32_t** | ตำแหน่งออฟเซ็ตเป็นไบท์ในอาร์เรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบท์ในอาร์เรย์ที่ระบุ เริ่มจากพารามิเตอร์ 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | จุดสิ้นสุดระยะไกล |

### ค่าที่คืนกลับ

จำนวนไบท์ที่ส่ง

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) เมธอด

ส่งข้อมูลที่ระบุไปยังจุดสิ้นสุดที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | ข้อมูลที่จะส่ง |
| offset | **int32_t** | ตำแหน่งออฟเซ็ตเป็นไบท์ในอาร์เรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบท์ในอาร์เรย์ที่ระบุ เริ่มจากพารามิเตอร์ 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | จุดสิ้นสุดระยะไกล |

### ค่าที่คืนกลับ

จำนวนไบท์ที่ส่ง

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) เมธอด

ส่งข้อมูลที่ระบุไปยังจุดสิ้นสุดที่ระบุ

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | ข้อมูลที่จะส่ง |
| offset | **int32_t** | ตำแหน่งออฟเซ็ตเป็นไบท์ในอาร์เรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบท์ในอาร์เรย์ที่ระบุ เริ่มจากพารามิเตอร์ 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | จุดสิ้นสุดระยะไกล |

### ค่าที่คืนกลับ

จำนวนไบท์ที่ส่ง

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) เมธอด

ส่งข้อมูลที่ระบุไปยังจุดสิ้นสุดที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ข้อมูลที่จะส่ง |
| size | **int32_t** | จำนวนไบท์ในอาร์เรย์ที่ระบุ |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | จุดสิ้นสุดระยะไกล |

### ค่าที่คืนกลับ

จำนวนไบท์ที่ส่ง

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) เมธอด

ส่งข้อมูลที่ระบุไปยังจุดสิ้นสุดที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | ข้อมูลที่จะส่ง |
| size | **int32_t** | จำนวนไบท์ในอาร์เรย์ที่ระบุ |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | จุดสิ้นสุดระยะไกล |

### ค่าที่คืนกลับ

จำนวนไบท์ที่ส่ง

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) เมธอด

ส่งข้อมูลที่ระบุไปยังจุดสิ้นสุดที่ระบุ

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | ข้อมูลที่จะส่ง |
| size | **int32_t** | จำนวนไบท์ในอาร์เรย์ที่ระบุ |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | จุดสิ้นสุดระยะไกล |

### ค่าที่คืนกลับ

จำนวนไบท์ที่ส่ง

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) เมธอด

ส่งข้อมูลที่ระบุไปยังจุดสิ้นสุดที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ข้อมูลที่จะส่ง |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | จุดสิ้นสุดระยะไกล |

### ค่าที่คืนกลับ

จำนวนไบท์ที่ส่ง

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) เมธอด

ส่งข้อมูลที่ระบุไปยังจุดสิ้นสุดที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | ข้อมูลที่จะส่ง |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | จุดสิ้นสุดระยะไกล |

### ค่าที่คืนกลับ

จำนวนไบท์ที่ส่ง

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) เมธอด

ส่งข้อมูลที่ระบุไปยังจุดสิ้นสุดที่ระบุ

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | ข้อมูลที่จะส่ง |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | จุดสิ้นสุดระยะไกล |

### ค่าที่คืนกลับ

จำนวนไบท์ที่ส่ง

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) เมธอด

ส่งข้อมูลที่ระบุไปยังจุดสิ้นสุดที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ข้อมูลที่จะส่ง |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | จุดสิ้นสุดระยะไกล |

### ค่าที่คืนกลับ

จำนวนไบท์ที่ส่ง

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) เมธอด

ส่งข้อมูลที่ระบุไปยังจุดสิ้นสุดที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | ข้อมูลที่จะส่ง |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | จุดสิ้นสุดระยะไกล |

### ค่าที่คืนกลับ

จำนวนไบท์ที่ส่ง

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) เมธอด

ส่งข้อมูลที่ระบุไปยังจุดสิ้นสุดที่ระบุ

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | ข้อมูลที่จะส่ง |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | จุดสิ้นสุดระยะไกล |

### ค่าที่คืนกลับ

จำนวนไบท์ที่ส่ง

## ดูเพิ่มเติม

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)