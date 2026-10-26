---
title: operator<<()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แทรกข้อมูลลงในสตรีมโดยใช้การเข้ารหัส UTF-8.
type: docs
weight: 716
url: /th/system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream&, const KeyValuePair<TKey, TValue>&) ฟังก์ชัน

แทรกข้อมูลลงในสตรีมโดยใช้การเข้ารหัส UTF-8.

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TKey | ประเภทของคีย์ |
| TValue | ประเภทของค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | std::ostream& | สตรีมเอาต์พุตสำหรับแทรกข้อมูล |
| pair | const [KeyValuePair](../keyvaluepair/)<TKey, TValue>& | [Data](../../system.data/) เพื่อแทรก |

### ค่าที่คืนกลับ

**stream**.

## System::Collections::Generic::operator<<(std::wostream&, const KeyValuePair<TKey, TValue>&) ฟังก์ชัน

แทรกข้อมูลลงในสตรีม.

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TKey | ประเภทของคีย์ |
| TValue | ประเภทของค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | std::wostream& | สตรีมเอาต์พุตสำหรับแทรกข้อมูล |
| pair | const [KeyValuePair](../keyvaluepair/)<TKey, TValue>& | [Data](../../system.data/) เพื่อแทรก |

### ค่าที่คืนกลับ

**stream**.

## ดูเพิ่มเติม

* คลาส [KeyValuePair](../keyvaluepair/)
* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)