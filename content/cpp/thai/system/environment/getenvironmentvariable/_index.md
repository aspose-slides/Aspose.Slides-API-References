---
title: GetEnvironmentVariable()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คืนค่าของตัวแปรสภาพแวดล้อมที่ระบุที่เชื่อมโยงกับกระบวนการปัจจันนี้
type: docs
weight: 287
url: /th/system/environment/getenvironmentvariable/
---
## Environment::GetEnvironmentVariable(const String\&) method


คืนค่าของตัวแปรสภาพแวดล้อมที่ระบุที่เชื่อมโยงกับกระบวนการปัจจุบัน.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| variable | const [String](../../string/)\& | สตริงที่มีชื่อของตัวแปรที่ต้องการเรียกคืน |

### ค่าที่คืนกลับ

ค่าของตัวแปรที่ระบุ

## Environment::GetEnvironmentVariable(const String\&, EnvironmentVariableTarget) method


คืนค่าของตัวแปรสภาพแวดล้อมที่ระบุจากตำแหน่งที่ระบุ.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable, EnvironmentVariableTarget target)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| variable | const [String](../../string/)\& | สตริงที่มีชื่อของตัวแปรที่ต้องการเรียกคืน |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | ตำแหน่งของตัวแปร |

### ค่าที่คืนกลับ

ค่าของตัวแปรที่ระบุ

## ดูเพิ่มเติม

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* คลาส [String](../../string/)
* Struct [Environment](../)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)