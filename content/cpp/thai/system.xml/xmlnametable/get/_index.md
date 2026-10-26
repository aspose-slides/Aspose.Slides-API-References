---
title: Get()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++ 
description: เมื่อทำการ override ในคลาสที่สืบทอด จะคืนสตริงที่ถูกทำให้เป็น atomized ซึ่งมีอักขระเดียวกันกับช่วงอักขระที่ระบุในอาเรย์ที่ให้มา.
type: docs
weight: 1
url: /th/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) เมธอด

เมื่อทำการ override ในคลาสที่สืบทอด, จะคืนสตริงที่ถูกทำให้เป็น atomized ซึ่งมีอักขระเดียวกันกับช่วงอักขระที่ระบุในอาเรย์ที่ให้มา.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | อาเรย์อักขระที่บรรจุชื่อที่ต้องการค้นหา. |
| offset | **int32_t** | ดัชนีเริ่มจากศูนย์ในอาเรย์ที่ระบุตำแหน่งอักขระแรกของชื่อ. |
| length | **int32_t** | จำนวนอักขระในชื่อ. |

### ค่ารีเทิร์น

สตริงที่ถูกทำให้เป็น atomized หรือ **nullptr** หากสตริงยังไม่ได้ถูกทำให้เป็น atomized. หาก **length** เป็นศูนย์, จะคืนค่า [String::Empty](../../../system/string/empty/).

## XmlNameTable::Get(const String\&) เมธอด

เมื่อทำการ override ในคลาสที่สืบทอด, จะคืนสตริงที่ถูกทำให้เป็น atomized ซึ่งมีค่าเดียวกับสตริงที่ระบุ.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | ชื่อที่ต้องการค้นหา. |

### ค่ารีเทิร์น

สตริงที่ถูกทำให้เป็น atomized หรือ **nullptr** หากสตริงยังไม่ได้ถูกทำให้เป็น atomized.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)