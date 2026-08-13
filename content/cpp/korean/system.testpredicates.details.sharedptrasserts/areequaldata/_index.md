---
title: AreEqualData()
second_title: Aspose.Slides for C++ API 참조
description: "요소에 대해 System::Object::Equals를 사용하여 두 컨테이너를 동등 비교합니다. SmartPtr 요소에 대해 작동합니다."
type: docs
weight: 14
url: /ko/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1&, const T2&) 함수


두 컨테이너를 요소에 대해 [System::Object::Equals](../../system/object/equals/)를 사용하여 동등 비교합니다. [SmartPtr](../../system/smartptr/) 요소에 대해 작동합니다.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```


### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T1 | LHS 컨테이너 타입. |
| T2 | RHS 컨테이너 타입. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | LHS 컨테이너 참조. |
| rhs | const T2\& | RHS 컨테이너 참조. |

### 반환 값

포함된 요소와 크기가 일치하면 true, 그렇지 않으면 false.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1&, const T2&) 함수


두 컨테이너를 요소에 대해 operator ==를 사용하여 동등 비교합니다. SmartPtr이 아닌 요소에 대해 작동합니다.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```


### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T1 | LHS 컨테이너 타입. |
| T2 | RHS 컨테이너 타입. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | LHS 컨테이너. |
| rhs | const T2\& | RHS 컨테이너. |

### 반환 값

포함된 요소와 크기가 일치하면 true, 그렇지 않으면 false.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T&, const T&) 함수


동일한 타입의 두 컨테이너를 동등 비교합니다. SmartPtr이 아닌 요소에 대해 작동합니다.

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```


### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T1 | LHS 컨테이너 타입. |
| T2 | RHS 컨테이너 타입. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T\& | LHS 컨테이너. |
| rhs | const T\& | RHS 컨테이너. |

### 반환 값

포함된 요소와 크기가 일치하면 true, 그렇지 않으면 false.

## 참고

* 구조체 [IsSmartPtr](../../system/issmartptr/)
* 네임스페이스 [System::TestPredicates::Details::SharedPtrAsserts](../)
* 라이브러리 [Aspose.Slides](../../)