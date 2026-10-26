---
title: GetSocketOption()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: คืนค่าที่สอดคล้องกับชื่อออปชันที่ระบุ
type: docs
weight: 729
url: /th/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) เมธอด


คืนค่าที่สอดคล้องกับชื่อออปชันที่ระบุ

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | ระดับออปชันของซ็อกเก็ต |
| optionName | [SocketOptionName](../../socketoptionname/) | ชื่อออปชัน |

### ค่าที่คืน

คืนค่าที่สอดคล้องกับชื่อออปชันที่ระบุ

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) เมธอด


ดึงค่าที่สอดคล้องกับชื่อออปชันที่ระบุ

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | ระดับออปชันของซ็อกเก็ต |
| optionName | [SocketOptionName](../../socketoptionname/) | ชื่อออปชัน |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | พารามิเตอร์เอาต์พุตที่ค่าที่สอดคล้องกันจะถูกกำหนด |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) เมธอด


คืนค่าที่สอดคล้องกับชื่อออปชันที่ระบุ

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | ระดับออปชันของซ็อกเก็ต |
| optionName | [SocketOptionName](../../socketoptionname/) | ชื่อออปชัน |
| optionLength | **int32_t** | ความยาวของออปชัน |

### ค่าที่คืน

คืนค่าที่สอดคล้องกับชื่อออปชันที่ระบุ

## ดูเพิ่มเติม

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)