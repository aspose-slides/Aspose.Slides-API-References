---
title: Add()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ทำการ atomize สตริงที่ระบุและเพิ่มลงใน NameTable.
type: docs
weight: 14
url: /th/system.xml/nametable/add/
---
## NameTable::Add(const String\&) เมธอด

ทำการ atomize สตริงที่ระบุและเพิ่มลงใน [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | สตริงที่ต้องการเพิ่ม |

### ค่าที่ส่งคืน

สตริงที่ถูก atomize หรือสตริงที่มีอยู่แล้วหากมีอยู่ใน [NameTable](../).

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) เมธอด

ทำการ atomize สตริงที่ระบุและเพิ่มลงใน [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | อาเรย์อักขระที่บรรจุสตริงที่ต้องการเพิ่ม |
| start | **int32_t** | ดัชนีเริ่มต้นแบบศูนย์ในอาเรย์ที่ระบุอักขระแรกของสตริง |
| len | **int32_t** | จำนวนอักขระในสตริง |

### ค่าที่ส่งคืน

สตริงที่ถูก atomize หรือสตริงที่มีอยู่แล้วหากมีอยู่ใน [NameTable](../). หาก **len** เป็นศูนย์, จะส่งกลับ [String::Empty](../../../system/string/empty/).

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [NameTable](../)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)