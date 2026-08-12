---
title: GetEnvironmentVariables()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนพจนานุกรมที่มีชื่อและค่าของตัวแปรสภาพแวดล้อมทั้งหมดที่เชื่อมโยงกับกระบวนการปัจจุบัน
type: docs
weight: 326
url: /th/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() เมธอด


Returns a dictionary containing all environment variables names and their values associated with the current process.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) เมธอด


Returns a dictionary containing all environment variables' names and their values from the specified location.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | ตำแหน่งของตัวแปร |

### ค่าที่ส่งคืน

A dictionary containing all environment variables' names and their values from the specified location

## ดูเพิ่มเติม

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* คลาส [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* คลาส [String](../../string/)
* Struct [Environment](../)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)