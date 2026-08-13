---
title: ComparerType< SharedPtr< T > >
second_title: Aspose.Slides for C++ API 레퍼런스
description: 요소를 'less' 의미론을 사용하여 비교합니다.
type: docs
weight: 157
url: /ko/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct

요소를 'less' 의미론을 사용하여 비교합니다.

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | 비교되는 요소 유형. |

## 메서드

| Method | Description |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | [IComparable](../../system/icomparable/) 인터페이스를 구현하는 포인터 타입을 비교합니다. |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | [IComparable](../../system/icomparable/) 인터페이스를 구현하지 않는 포인터 타입을 비교합니다. |

## 참고

* 네임스페이스 [System::Collections::Generic::Details](../)
* 라이브러리 [Aspose.Slides](../../)