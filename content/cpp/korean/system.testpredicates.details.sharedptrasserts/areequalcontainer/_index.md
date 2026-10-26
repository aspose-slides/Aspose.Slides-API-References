---
title: AreEqualContainer()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 요소에 대해 operator == 를 사용하여 두 컨테이너를 동등 비교합니다. non-SmartPtr 요소에 대해 작동합니다.
type: docs
weight: 1
url: /ko/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) function

두 컨테이너를 요소에 대해 operator == 를 사용하여 동등 비교합니다. non-SmartPtr 요소에 대해 작동합니다.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 컨테이너 유형. |
| T2 | RHS 컨테이너 유형. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| lhs | const T1\& | LHS 컨테이너. |
| rhs | const T2\& | RHS 컨테이너. |

### 반환 값

포함된 요소와 크기가 일치하면 true, 그렇지 않으면 false.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) function

두 컨테이너를 요소에 대해 [System::Object::Equals](../../system/object/equals/) 를 사용하여 동등 비교합니다. [SmartPtr](../../system/smartptr/) 요소에 대해 작동합니다.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 컨테이너 유형. |
| T2 | RHS 컨테이너 유형. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| lhs | const T1\& | LHS 컨테이너 참조. |
| rhs | const T2\& | RHS 컨테이너 참조. |

### 반환 값

포함된 요소와 크기가 일치하면 true, 그렇지 않으면 false.

## 참고

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)