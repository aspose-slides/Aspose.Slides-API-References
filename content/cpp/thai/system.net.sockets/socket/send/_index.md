---
title: Send()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต
type: docs
weight: 638
url: /th/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) method

ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ข้อมูลที่ต้องส่ง |
| size | **int32_t** | จำนวนไบต์จากข้อมูลที่ระบุที่ต้องส่ง |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |

### ค่ารีเทิร์น

จำนวนไบต์ที่ส่งแล้ว

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) method

ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | ข้อมูลที่ต้องส่ง |
| size | **int32_t** | จำนวนไบต์จากข้อมูลที่ระบุที่ต้องส่ง |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |

### ค่ารีเทิร์น

จำนวนไบต์ที่ส่งแล้ว

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) method

ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | ข้อมูลที่ต้องส่ง |
| size | **int32_t** | จำนวนไบต์จากข้อมูลที่ระบุที่ต้องส่ง |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |

### ค่ารีเทิร์น

จำนวนไบต์ที่ส่งแล้ว

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) method

ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ข้อมูลที่ต้องส่ง |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |

### ค่ารีเทิร์น

จำนวนไบต์ที่ส่งแล้ว

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) method

ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | ข้อมูลที่ต้องส่ง |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |

### ค่ารีเทิร์น

จำนวนไบต์ที่ส่งแล้ว

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) method

ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | ข้อมูลที่ต้องส่ง |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |

### ค่ารีเทิร์น

จำนวนไบต์ที่ส่งแล้ว

## Socket::Send(System::ArrayPtr\<uint8_t\>) method

ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ข้อมูลที่ต้องส่ง |

### ค่ารีเทิร์น

จำนวนไบต์ที่ส่งแล้ว

## Socket::Send(System::Details::ArrayView\<uint8_t\>) method

ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | ข้อมูลที่ต้องส่ง |

### ค่ารีเทิร์น

จำนวนไบต์ที่ส่งแล้ว

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) method

ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | ข้อมูลที่ต้องส่ง |

### ค่ารีเทิร์น

จำนวนไบต์ที่ส่งแล้ว

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) method

ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | คอลเล็กชันของอาร์เรย์ไบต์ที่ต้องส่งข้อมูลจากนั้น |

### ค่ารีเทิร์น

จำนวนไบต์ที่ส่งแล้ว

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) method

ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | คอลเล็กชันของอาร์เรย์ไบต์ที่ต้องส่งข้อมูลจากนั้น |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |

### ค่ารีเทิร์น

จำนวนไบต์ที่ส่งแล้ว

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) method

ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | คอลเล็กชันของอาร์เรย์ไบต์ที่ต้องส่งข้อมูลจากนั้น |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |
| errorCode | [SocketError](../../socketerror/)\& | พารามิเตอร์ผลลัพธ์ที่รหัสข้อผิดพลาดจะถูกกำหนดเมื่อการส่งล้มเหลว |

### ค่ารีเทิร์น

จำนวนไบต์ที่ส่งแล้ว

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) method

ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ข้อมูลที่ต้องส่ง |
| offset | **int32_t** | การออฟเซ็ตเป็นไบต์ในอาร์เรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ในอาร์เรย์ที่ระบุเริ่มต้นจากพารามิเตอร์ 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |

### ค่ารีเทิร์น

จำนวนไบต์ที่ส่งแล้ว

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) method

ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | ข้อมูลที่ต้องส่ง |
| offset | **int32_t** | การออฟเซ็ตเป็นไบต์ในอาร์เรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ในอาร์เรย์ที่ระบุเริ่มต้นจากพารามิเตอร์ 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |

### ค่ารีเทิร์น

จำนวนไบต์ที่ส่งแล้ว

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) method

ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | ข้อมูลที่ต้องส่ง |
| offset | **int32_t** | การออฟเซ็ตเป็นไบต์ในอาร์เรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ในอาร์เรย์ที่ระบุเริ่มต้นจากพารามิเตอร์ 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |

### ค่ารีเทิร์น

จำนวนไบต์ที่ส่งแล้ว

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method

ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ข้อมูลที่ต้องส่ง |
| offset | **int32_t** | การออฟเซ็ตเป็นไบต์ในอาร์เรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ในอาร์เรย์ที่ระบุเริ่มต้นจากพารามิเตอร์ 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |
| errorCode | [SocketError](../../socketerror/)\& | พารามิเตอร์ผลลัพธ์ที่รหัสข้อผิดพลาดจะถูกกำหนดเมื่อการส่งล้มเหลว |

### ค่ารีเทิร์น

จำนวนไบต์ที่ส่งแล้ว

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method

ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | ข้อมูลที่ต้องส่ง |
| offset | **int32_t** | การออฟเซ็ตเป็นไบต์ในอาร์เรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ในอาร์เรย์ที่ระบุเริ่มต้นจากพารามิเตอร์ 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |
| errorCode | [SocketError](../../socketerror/)\& | พารามิเตอร์ผลลัพธ์ที่รหัสข้อผิดพลาดจะถูกกำหนดเมื่อการส่งล้มเหลว |

### ค่ารีเทิร์น

จำนวนไบต์ที่ส่งแล้ว

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) method

ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | ข้อมูลที่ต้องส่ง |
| offset | **int32_t** | การออฟเซ็ตเป็นไบต์ในอาร์เรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ในอาร์เรย์ที่ระบุเริ่มต้นจากพารามิเตอร์ 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |
| errorCode | [SocketError](../../socketerror/)\& | พารามิเตอร์ผลลัพธ์ที่รหัสข้อผิดพลาดจะถูกกำหนดเมื่อการส่งล้มเหลว |

### ค่ารีเทิร์น

จำนวนไบต์ที่ส่งแล้ว

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