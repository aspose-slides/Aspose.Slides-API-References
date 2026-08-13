---
title: NotNullAreEqualHelper()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 추상 컬렉션을 동등 비교합니다.
type: docs
weight: 66
url: /ko/system.testpredicates.details.sharedptrasserts/notnullareequalhelper/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualHelper(const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) 함수

추상 컬렉션을 동등 비교합니다.

```cpp
template<typename T> bool System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualHelper(const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 요소 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | 좌변 값. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | 우변 값. |

### 반환 값

gtest 스타일 어설션 결과.

## 참조

* 타입정의 [SharedPtr](../../system/sharedptr/)
* 클래스 [ICollection](../../system.collections.generic/icollection/)
* 네임스페이스 [System::TestPredicates::Details::SharedPtrAsserts](../)
* 라이브러리 [Aspose.Slides](../../)