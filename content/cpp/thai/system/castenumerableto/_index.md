---
title: CastEnumerableTo()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ทำการแคสแบบชัดเจนของสมาชิกของอ็อบเจ็กต์ enumerable ที่ระบุเป็นประเภทที่ต่างกัน
type: docs
weight: 2965
url: /th/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) ฟังก์ชัน

ทำการแคสแบบชัดเจนของสมาชิกของอ็อบเจ็กต์ enumerable ที่ระบุเป็นประเภทที่ต่างกัน

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| To | ประเภทที่จะทำการแคสแบบสแตติกสมาชิกของอ็อบเจ็กต์ enumerable ไปเป็น |
| From | ประเภทของอ็อบเจ็กต์ enumerable |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| enumerable | const From\& | อ็อบเจ็กต์ enumerable ที่บรรจุสมาชิกที่จะทำการแคส |

### ค่าที่ส่งกลับ

พอยน์เตอร์ไปยังคอลเลกชันใหม่ที่บรรจุสมาชิกประเภท **To** ที่เทียบเท่ากับสมาชิกของ **enumerable**

## System::CastEnumerableTo(const From\&) ฟังก์ชัน

ทำการแคสแบบชัดเจนของสมาชิกของอ็อบเจ็กต์ enumerable ที่ระบุเป็นประเภทที่ต่างกัน

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| To | ประเภทที่จะทำการแคสแบบสแตติกสมาชิกของอ็อบเจ็กต์ enumerable ไปเป็น |
| From | ประเภทของอ็อบเจ็กต์ enumerable |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| enumerable | const From\& | เป็นอ็อบเจ็กต์ลูกของ Enumerable ที่มีเมธอด get_Count นิยามไว้และบรรจุสมาชิกที่ต้องการแคส |

### ค่าที่ส่งกลับ

พอยน์เตอร์ไปยังคอลเลกชันใหม่ที่บรรจุสมาชิกประเภท **To** ที่เทียบเท่ากับสมาชิกของ **enumerable**

## ดูเพิ่มเติม

* คลาส [ListPtr](../../system.collections.generic/listptr/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)