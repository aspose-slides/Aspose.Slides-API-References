---
title: AnyOfDecimal
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ตรวจสอบว่าอาร์กิวเมนต์ประเภทอย่างน้อยหนึ่งตัวคือ System::Decimal หากเป็นเช่นนั้น จะตั้งค่า value member ให้เป็น true มิฉะนั้นจะเป็น false."
type: docs
weight: 92
url: /th/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef


ตรวจสอบว่าอาร์กิวเมนต์ประเภทอย่างน้อยหนึ่งตัวคือ [System::Decimal](../../system/decimal/) หากเป็นเช่นนั้น จะตั้งค่า value member ให้เป็น true มิฉะนั้นจะเป็น false.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal = typedef std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```


## ดูเพิ่มเติม

* เนมสเปซ [System::TestPredicates::TypeTraits](../)
* ไลบรารี [Aspose.Slides](../../)