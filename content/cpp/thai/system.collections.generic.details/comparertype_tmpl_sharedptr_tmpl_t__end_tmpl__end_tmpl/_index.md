---
title: ComparerType< SharedPtr< T > >
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เปรียบเทียบองค์ประกอบโดยใช้หลักการ 'less'
type: docs
weight: 157
url: /th/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct

เปรียบเทียบองค์ประกอบโดยใช้การทำงานแบบ 'less' semantics.

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบที่เปรียบเทียบ. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | เปรียบเทียบประเภทพอยน์เตอร์ที่ทำการใช้งานอินเทอร์เฟซ [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | เปรียบเทียบประเภทพอยน์เตอร์ที่ไม่ได้ทำการใช้งานอินเทอร์เฟซ [IComparable](../../system/icomparable/). |

## ดูเพิ่มเติม

* เนมสเปซ [System::Collections::Generic::Details](../)
* ไลบรารี [Aspose.Slides](../../)