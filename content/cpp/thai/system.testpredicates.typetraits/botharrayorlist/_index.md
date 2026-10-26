---
title: BothArrayOrList
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตรวจสอบว่าทั้งสองอาร์กิวเมนต์ประเภทเป็นอาเรย์หรือรายการหรือไม่ หากเป็นเช่นนั้น สมาชิก value จะถูกตั้งค่าเป็น true มิฉะนั้นจะตั้งค่าเป็น false.
type: docs
weight: 131
url: /th/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef


ตรวจสอบว่าทั้งสองอาร์กิวเมนต์ประเภทเป็นอาเรย์หรือรายการหรือไม่ หากเป็นเช่นนั้น สมาชิก value จะถูกตั้งค่าเป็น true มิฉะนั้นจะตั้งค่าเป็น false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```


## ดูเพิ่มเติม

* เนมสเปซ [System::TestPredicates::TypeTraits](../)
* ไลบรารี [Aspose.Slides](../../)