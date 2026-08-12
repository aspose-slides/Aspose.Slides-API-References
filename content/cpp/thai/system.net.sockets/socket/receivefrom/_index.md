---
title: ReceiveFrom()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: รับข้อมูลจากจุดหมายที่ระบุและเขียนลงในอาเรย์ไบต์ที่ระบุ
type: docs
weight: 690
url: /th/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) เมธอด

รับข้อมูลจากจุดหมายที่กำหนดและเขียนลงในอาเรย์ไบต์ที่กำหนด

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาเรย์ที่กำหนด |
| size | **int32_t** | จำนวนไบต์ที่จะรับซึ่งจะถูกกำหนดให้กับอาเรย์ไบต์ที่กำหนดจากตำแหน่ง 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | จุดหมายปลายทางระยะไกล |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่รับ

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) เมธอด

รับข้อมูลจากจุดหมายที่กำหนดและเขียนลงในอาเรย์ไบต์ที่กำหนด

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาเรย์ที่กำหนด |
| size | **int32_t** | จำนวนไบต์ที่จะรับซึ่งจะถูกกำหนดให้กับอาเรย์ไบต์ที่กำหนดจากตำแหน่ง 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | จุดหมายปลายทางระยะไกล |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่รับ

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) เมธอด

รับข้อมูลจากจุดหมายที่กำหนดและเขียนลงในอาเรย์ไบต์ที่กำหนด

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาเรย์ที่กำหนด |
| size | **int32_t** | จำนวนไบต์ที่จะรับซึ่งจะถูกกำหนดให้กับอาเรย์ไบต์ที่กำหนดจากตำแหน่ง 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | จุดหมายปลายทางระยะไกล |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่รับ

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) เมธอด

รับข้อมูลจากจุดหมายที่กำหนดและเขียนลงในอาเรย์ไบต์ที่กำหนด

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| size | **int32_t** | จำนวนไบต์ที่จะรับซึ่งจะถูกกำหนดให้กับอาเรย์ไบต์ที่กำหนดจากตำแหน่ง 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | จุดหมายปลายทางระยะไกล |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่รับ

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) เมธอด

รับข้อมูลจากจุดหมายที่กำหนดและเขียนลงในอาเรย์ไบต์ที่กำหนด

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| size | **int32_t** | จำนวนไบต์ที่จะรับซึ่งจะถูกกำหนดให้กับอาเรย์ไบต์ที่กำหนดจากตำแหน่ง 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | จุดหมายปลายทางระยะไกล |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่รับ

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) เมธอด

รับข้อมูลจากจุดหมายที่กำหนดและเขียนลงในอาเรย์ไบต์ที่กำหนด

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| size | **int32_t** | จำนวนไบต์ที่จะรับซึ่งจะถูกกำหนดให้กับอาเรย์ไบต์ที่กำหนดจากตำแหน่ง 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | จุดหมายปลายทางระยะไกล |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่รับ

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) เมธอด

รับข้อมูลจากจุดหมายที่กำหนดและเขียนลงในอาเรย์ไบต์ที่กำหนด

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | จุดหมายปลายทางระยะไกล |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่รับ

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) เมธอด

รับข้อมูลจากจุดหมายที่กำหนดและเขียนลงในอาเรย์ไบต์ที่กำหนด

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | จุดหมายปลายทางระยะไกล |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่รับ

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) เมธอด

รับข้อมูลจากจุดหมายที่กำหนดและเขียนลงในอาเรย์ไบต์ที่กำหนด

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | จุดหมายปลายทางระยะไกล |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่รับ

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) เมธอด

รับข้อมูลจากจุดหมายที่กำหนดและเขียนลงในอาเรย์ไบต์ที่กำหนด

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | จุดหมายปลายทางระยะไกล |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่รับ

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) เมธอด

รับข้อมูลจากจุดหมายที่กำหนดและเขียนลงในอาเรย์ไบต์ที่กำหนด

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | จุดหมายปลายทางระยะไกล |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่รับ

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) เมธอด

รับข้อมูลจากจุดหมายที่กำหนดและเขียนลงในอาเรย์ไบต์ที่กำหนด

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | จุดหมายปลายทางระยะไกล |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่รับ

## ดูเพิ่มเติม

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)