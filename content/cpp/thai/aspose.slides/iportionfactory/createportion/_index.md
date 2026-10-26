---
title: CreatePortion()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างส่วนข้อความว่าง.
type: docs
weight: 1
url: /th/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() เมธอด


สร้างส่วนข้อความว่าง.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```


### ค่าที่ส่งคืน

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) เมธอด


สร้างส่วนข้อความจากสตริงที่ระบุ.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | สตริง. |

### ค่าที่ส่งคืน

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) เมธอด


สร้างส่วนโดยใช้ข้อมูลส่วนที่ระบุ.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | ส่วนที่จะใช้. |

### ค่าที่ส่งคืน

[Portion](../../portion/).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IPortion](../../iportion/)
* คลาส [IPortionFactory](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)