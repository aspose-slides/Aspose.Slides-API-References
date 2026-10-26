---
title: NetworkStream()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: สร้างอินสแตนซ์ใหม่.
type: docs
weight: 170
url: /th/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) constructor

สร้างอินสแตนซ์ใหม่.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | ซ็อกเก็ตที่ใช้สำหรับส่งและรับข้อมูล |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) constructor

สร้างอินสแตนซ์ใหม่.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | ซ็อกเก็ตที่ใช้สำหรับส่งและรับข้อมูล |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | ระบุประเภทการเข้าถึงที่ให้กับอินสแตนซ์บนซ็อกเก็ตที่ระบุ |
| ownsSocket | **bool** | ค่าที่ระบุว่าปัจจุบันอินสแตนซ์เป็นเจ้าของซ็อกเก็ตที่ระบุเมื่อค่าเป็น true |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) constructor

สร้างอินสแตนซ์ใหม่.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | ซ็อกเก็ตที่ใช้สำหรับส่งและรับข้อมูล |
| ownsSocket | **bool** | ค่าที่ระบุว่าปัจจุบันอินสแตนซ์เป็นเจ้าของซ็อกเก็ตที่ระบุเมื่อค่าเป็น true |

## ดูเพิ่มเติม

* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../../socket/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)