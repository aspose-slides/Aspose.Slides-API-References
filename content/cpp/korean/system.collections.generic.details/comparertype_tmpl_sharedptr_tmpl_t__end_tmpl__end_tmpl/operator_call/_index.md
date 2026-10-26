---
title: operator()()
second_title: Aspose.Slides for C++ API 레퍼런스
description: IComparable 인터페이스를 구현하는 포인터 타입을 비교합니다.
type: docs
weight: 1
url: /ko/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const method

포인터 타입이 [IComparable](../../../system/icomparable/) 인터페이스를 구현하는 경우를 비교합니다.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Q | 비교할 타입. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | 좌변 값. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | 우변 값. |

### 반환값

**a**가 **b**보다 작다고 판단되면 true, 그렇지 않으면 false.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const method

포인터 타입이 [IComparable](../../../system/icomparable/) 인터페이스를 구현하지 않는 경우를 비교합니다.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Q | 비교할 타입. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | 좌변 값. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | 우변 값. |

### 반환값

**a**가 **b**보다 작다고 판단되면 true, 그렇지 않으면 false.

## 관련 항목

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IComparable](../../../system/icomparable/)
* 구조체 [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* 구조체 [ComparerType< SharedPtr< T > >](../)
* 네임스페이스 [System::Collections::Generic::Details](../../)
* 라이브러리 [Aspose.Slides](../../../)