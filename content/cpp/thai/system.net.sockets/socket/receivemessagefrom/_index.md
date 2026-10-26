---
title: ReceiveMessageFrom()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: รับข้อมูลจากจุดสิ้นสุดที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ
type: docs
weight: 677
url: /th/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) เมธอด


รับข้อมูลจากจุดสิ้นสุดที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาร์เรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนดค่า |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาร์เรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ที่จะรับซึ่งจะถูกกำหนดค่าให้กับอาร์เรย์ไบต์ที่ระบุจากดัชนี 'offset' |
| socketFlags | [SocketFlags](../../socketflags/)\& | พฤติกรรมการรับ |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | จุดปลายทางระยะไกล |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | พารามิเตอร์ผลลัพธ์ที่ข้อมูลเกี่ยวกับแพ็กเก็ตจะถูกกำหนดค่า |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่รับได้

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) เมธอด


รับข้อมูลจากจุดสิ้นสุดที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | อาร์เรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนดค่า |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาร์เรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ที่จะรับซึ่งจะถูกกำหนดค่าให้กับอาร์เรย์ไบต์ที่ระบุจากดัชนี 'offset' |
| socketFlags | [SocketFlags](../../socketflags/)\& | พฤติกรรมการรับ |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | จุดปลายทางระยะไกล |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | พารามิเตอร์ผลลัพธ์ที่ข้อมูลเกี่ยวกับแพ็กเก็ตจะถูกกำหนดค่า |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่รับได้

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) เมธอด


รับข้อมูลจากจุดสิ้นสุดที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | อาร์เรย์ไบต์ที่ข้อมูลที่รับจะถูกกำหนดค่า |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาร์เรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ที่จะรับซึ่งจะถูกกำหนดค่าให้กับอาร์เรย์ไบต์ที่ระบุจากดัชนี 'offset' |
| socketFlags | [SocketFlags](../../socketflags/)\& | พฤติกรรมการรับ |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | จุดปลายทางระยะไกล |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | พารามิเตอร์ผลลัพธ์ที่ข้อมูลเกี่ยวกับแพ็กเก็ตจะถูกกำหนดค่า |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่รับได้

## ดูเพิ่มเติม

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [IPPacketInformation](../../ippacketinformation/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)