---
title: operator()()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เปรียบเทียบประเภทพอยเตอร์ที่ทำการทำงานตามอินเทอร์เฟซ IComparable.
type: docs
weight: 1
url: /th/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const เมธอด

เปรียบเทียบประเภทพอยเตอร์ที่ทำการทำงานตามอินเทอร์เฟซ [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Q | ประเภทที่ต้องการเปรียบเทียบ. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | ค่าด้านซ้าย. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | ค่าด้านขวา. |

### ค่าที่ส่งกลับ

True หาก **a** ถูกพิจารณาว่าน้อยกว่า **b**, false ในกรณีอื่น.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const เมธอด

เปรียบเทียบประเภทพอยเตอร์ที่ไม่ได้ทำการทำงานตามอินเทอร์เฟซ [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Q | ประเภทที่ต้องการเปรียบเทียบ. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | ค่าด้านซ้าย. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | ค่าด้านขวา. |

### ค่าที่ส่งกลับ

True หาก **a** ถูกพิจารณาว่าน้อยกว่า **b**, false ในกรณีอื่น.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Struct [ComparerType< SharedPtr< T > >](../)
* เนมสเปซ [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)