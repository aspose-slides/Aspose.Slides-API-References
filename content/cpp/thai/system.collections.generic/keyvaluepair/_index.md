---
title: KeyValuePair
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: "คู่ของคีย์และค่า ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านไปยังฟังก์ชันโดยค่า หรือโดยการอ้างอิง ห้ามใช้คลาส System::SmartPtr เพื่อจัดการอ็อบเจกต์ของประเภทนี้."
type: docs
weight: 378
url: /th/system.collections.generic/keyvaluepair/
---
## KeyValuePair คลาส

คู่ของคีย์และค่า ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านไปยังฟังก์ชันโดยค่า หรือโดยการอ้างอิง ห้ามใช้คลาส [System::SmartPtr](../../system/smartptr/) เพื่อจัดการอ็อบเจกต์ของประเภทนี้

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## เมธอด

| Method | Description |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | ดึงคีย์ |
| const TValue\& [get_Value](./get_value/)() const | ดึงค่า |
| int [GetHashCode](./gethashcode/)() const | คำนวณแฮชของคู่คีย์-ค่าโดยการ XOR แฮชของคีย์และค่าที่เป็นคู่กัน |
| **bool** [IsNull](./isnull/)() const | คืนค่า false เสมอ |
|  [KeyValuePair](./keyvaluepair/)() | ตัวเริ่มต้นคู่คีย์-ค่าเป็น null |
|  [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | คอนสตรัคเตอร์ |
|  [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | คอนสตรัคเตอร์การแปลงประเภท |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | แพทช์สำหรับคลาสที่สืบทอดจาก IComparer<KeyValuePair<TKey, TValue>> ไม่ได้เปรียบเทียบอะไรเลย |
| [String](../../system/string/) [ToString](./tostring/)() const | แปลงคู่คีย์-ค่าเป็นสตริง |

## ดูเพิ่มเติม

* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)