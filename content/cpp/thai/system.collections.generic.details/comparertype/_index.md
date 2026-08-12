---
title: ComparerType
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เปรียบเทียบองค์ประกอบโดยใช้หลักการ 'less'.
type: docs
weight: 144
url: /th/system.collections.generic.details/comparertype/
---
## ComparerType struct

เปรียบเทียบองค์ประกอบโดยใช้หลักการ 'less'.

```cpp
template<typename T>class ComparerType
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบที่เปรียบเทียบ. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | เปรียบเทียบประเภทค่าที่ทำการ implement อินเทอร์เฟซ [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | เปรียบเทียบประเภทค่าพื้นฐานและอ็อบเจ็กต์ที่ไม่ได้ทำการ implement อินเทอร์เฟซ [IComparable](../../system/icomparable/). |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | เปรียบเทียบประเภทจุดลอย. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Collections::Generic::Details](../)
* ไลบรารี [Aspose.Slides](../../)