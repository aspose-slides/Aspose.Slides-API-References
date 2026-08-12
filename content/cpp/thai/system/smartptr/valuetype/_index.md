---
title: ValueType
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "ประเภทการจัดเก็บของอาเรย์ที่ชี้. มีความหมายเฉพาะเมื่อ T เป็นการทำ specialization ของ System::Array."
type: docs
weight: 508
url: /th/system/smartptr/valuetype/
---
## ValueType typedef

Storage type of pointed array. Only meaningful if T is a specialization of [System::Array](../../array/).

```cpp
using System::SmartPtr< T >::ValueType =  typename System::Details::SelectType<typename System::Details::ArrayTypeResolver<T>::value_type>::type
```

## ดูเพิ่มเติม

* คลาส [SmartPtr](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)