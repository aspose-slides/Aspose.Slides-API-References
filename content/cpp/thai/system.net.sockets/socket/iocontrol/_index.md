---
title: IOControl()
second_title: Aspose.Slides สำหรับ API ของ C++
description: ตั้งค่ารูปแบบการทำงานระดับต่ำสำหรับซ็อกเก็ต
type: docs
weight: 703
url: /th/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) เมธอด

ตั้งค่ารูปแบบการทำงานระดับต่ำสำหรับซ็อกเก็ต

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ioControlCode | **int32_t** | รหัสควบคุมของการดำเนินการที่ต้องการทำ |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ไบต์ที่บรรจุข้อมูลเข้า |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ไบต์ที่บรรจุข้อมูลออก |

### ค่าที่ส่งกลับ

จำนวนไบต์ในพารามิเตอร์ **optionOutValue**

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) เมธอด

ตั้งค่ารูปแบบการทำงานระดับต่ำสำหรับซ็อกเก็ต

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | รหัสควบคุมของการดำเนินการที่ต้องการทำ |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ไบต์ที่บรรจุข้อมูลเข้า |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ไบต์ที่บรรจุข้อมูลออก |

### ค่าที่ส่งกลับ

จำนวนไบต์ในพารามิเตอร์ **optionOutValue**

## ดูเพิ่มเติม

* Enum [IOControlCode](../../iocontrolcode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)