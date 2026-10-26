---
title: Get()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืนสตริงที่ทำให้เป็นอัตมโนมิฟายด้วยค่าที่ระบุ
type: docs
weight: 27
url: /th/system.xml/nametable/get/
---
## NameTable::Get(const String\&) เมธอด


ส่งคืนสตริงที่ทำให้เป็นอัตมโนมิฟายด้วยค่าที่ระบุ

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | ชื่อที่ต้องการค้นหา |

### ค่ารีเทิร์น

สตริงที่ทำให้เป็นอัตมโนมิฟายหรือ **nullptr** หากสตริงยังไม่ได้รับการทำให้เป็นอัตมโนมิฟาย

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) เมธอด


ส่งคืนสตริงที่ทำให้เป็นอัตมโนมิฟายที่มีอักขระเดียวกับช่วงอักขระที่ระบุในอาร์เรย์ที่ให้

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | อาร์เรย์อักขระที่มีชื่อที่ต้องการค้นหา |
| start | **int32_t** | ดัชนีเริ่มจากศูนย์ในอาเรย์ระบุอักขระแรกของชื่อ |
| len | **int32_t** | จำนวนอักขระในชื่อ |

### ค่ารีเทิร์น

สตริงที่ทำให้เป็นอัตมโนมิฟายหรือ **nullptr** หากสตริงยังไม่ได้รับการทำให้เป็นอัตมโนมิฟาย หาก **len** มีค่าเป็นศูนย์ จะคืนค่า [String::Empty](../../../system/string/empty/)

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [NameTable](../)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)