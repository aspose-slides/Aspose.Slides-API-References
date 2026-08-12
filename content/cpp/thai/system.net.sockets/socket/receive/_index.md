---
title: Receive()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ.
type: docs
weight: 664
url: /th/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) เมธอด

รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| size | **int32_t** | จำนวนไบต์ที่ต้องรับ |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |

### ค่าที่ส่งคืน

จำนวนไบต์ที่รับ

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) เมธอด

รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| size | **int32_t** | จำนวนไบต์ที่ต้องรับ |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |

### ค่าที่ส่งคืน

จำนวนไบต์ที่รับ

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) เมธอด

รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| size | **int32_t** | จำนวนไบต์ที่ต้องรับ |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |

### ค่าที่ส่งคืน

จำนวนไบต์ที่รับ

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) เมธอด

รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |

### ค่าที่ส่งคืน

จำนวนไบต์ที่รับ

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) เมธอด

รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |

### ค่าที่ส่งคืน

จำนวนไบต์ที่รับ

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) เมธอด

รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |

### ค่าที่ส่งคืน

จำนวนไบต์ที่รับ

## Socket::Receive(System::ArrayPtr\<uint8_t\>) เมธอด

รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |

### ค่าที่ส่งคืน

จำนวนไบต์ที่รับ

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) เมธอด

รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |

### ค่าที่ส่งคืน

จำนวนไบต์ที่รับ

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) เมธอด

รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |

### ค่าที่ส่งคืน

จำนวนไบต์ที่รับ

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) เมธอด

รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาเรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ที่ต้องรับซึ่งจะถูกกำหนดให้กับอาเรย์ไบต์ที่ระบุจากตำแหน่ง 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |

### ค่าที่ส่งคืน

จำนวนไบต์ที่รับ

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) เมธอด

รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาเรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ที่ต้องรับซึ่งจะถูกกำหนดให้กับอาเรย์ไบต์ที่ระบุจากตำแหน่ง 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |

### ค่าที่ส่งคืน

จำนวนไบต์ที่รับ

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) เมธอด

รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาเรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ที่ต้องรับซึ่งจะถูกกำหนดให้กับอาเรย์ไบต์ที่ระบุจากตำแหน่ง 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |

### ค่าที่ส่งคืน

จำนวนไบต์ที่รับ

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) เมธอด

รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาเรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ที่ต้องรับซึ่งจะถูกกำหนดให้กับอาเรย์ไบต์ที่ระบุจากตำแหน่ง 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |
| errorCode | [SocketError](../../socketerror/)\& | พารามิเตอร์ผลลัพธ์ที่รหัสข้อผิดพลาดจะถูกกำหนดเมื่อการรับล้มเหลว |

### ค่าที่ส่งคืน

จำนวนไบต์ที่รับ

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) เมธอด

รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาเรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ที่ต้องรับซึ่งจะถูกกำหนดให้กับอาเรย์ไบต์ที่ระบุจากตำแหน่ง 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |
| errorCode | [SocketError](../../socketerror/)\& | พารามิเตอร์ผลลัพธ์ที่รหัสข้อผิดพลาดจะถูกกำหนดเมื่อการรับล้มเหลว |

### ค่าที่ส่งคืน

จำนวนไบต์ที่รับ

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) เมธอด

รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาเรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ที่ต้องรับซึ่งจะถูกกำหนดให้กับอาเรย์ไบต์ที่ระบุจากตำแหน่ง 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |
| errorCode | [SocketError](../../socketerror/)\& | พารามิเตอร์ผลลัพธ์ที่รหัสข้อผิดพลาดจะถูกกำหนดเมื่อการรับล้มเหลว |

### ค่าที่ส่งคืน

จำนวนไบต์ที่รับ

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) เมธอด

รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |

### ค่าที่ส่งคืน

จำนวนไบต์ที่รับ

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) เมธอด

รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |

### ค่าที่ส่งคืน

จำนวนไบต์ที่รับ

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) เมธอด

รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | อาเรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนด |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |
| errorCode | [SocketError](../../socketerror/)\& | พารามิเตอร์ผลลัพธ์ที่รหัสข้อผิดพลาดจะถูกกำหนดเมื่อการรับล้มเหลว |

### ค่าที่ส่งคืน

จำนวนไบต์ที่รับ

## ดูเพิ่มเติม

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)