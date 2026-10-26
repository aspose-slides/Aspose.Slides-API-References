---
title: ConvertAll()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างรายการขององค์ประกอบที่ถูกแปลงเป็นประเภทที่ต่างกัน
type: docs
weight: 352
url: /th/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) เมธอด

สร้างรายการขององค์ประกอบที่ถูกแปลงเป็นประเภทที่แตกต่างกัน.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| OutputType | ประเภทของอิลิเมนต์ในรายการผลลัพธ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | คอนเวอร์เตอร์ที่ใช้สำหรับการแปลงรายการ |

### ค่าที่คืน

รายการใหม่ที่สร้างขึ้นซึ่งประกอบด้วยอิลิเมนต์ที่แปลงแล้ว.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* คลาส [List](../)
* เนมสเปซ [System::Collections::Generic](../../)
* ไลบรารี [Aspose.Slides](../../../)