---
title: AreFPandArithmetic
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตรวจสอบว่า T1 เป็น arithmetic และ T2 เป็น floating point, หรือในทางกลับกัน หากเป็นเช่นนั้น จะตั้งค่า member value เป็น true, มิฉะนั้นจะเป็น false.
type: docs
weight: 79
url: /th/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef


ตรวจสอบว่า **T1** เป็น arithmetic และ **T2** เป็น floating point, หรือในทางกลับกัน หากเป็นเช่นนั้น จะตั้งค่า member value เป็น true, หากไม่เป็นจะเป็น false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```


## ดูเพิ่มเติม

* เนมสเปซ [System::TestPredicates::TypeTraits](../)
* ไลบรารี [Aspose.Slides](../../)