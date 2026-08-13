---
title: AreNotEqual()
second_title: Aspose.Slides for C++ API 레퍼런스
description: AreNotEqual 어설션 변환을 위한 인수를 불일치 비교합니다.
type: docs
weight: 131
url: /ko/system.testpredicates.details.sharedptrasserts/arenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *, const char *, const T1\&, const T2\&) function

Not-equal-compares arguments for AreNotEqual assertion translation.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 객체 유형. |
| T2 | RHS 객체 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const T1\& | LHS 값. |
| rhs | const T2\& | RHS 값. |

### 반환 값

gtest 스타일의 어설션 결과.

## 참고

* 네임스페이스 [System::TestPredicates::Details::SharedPtrAsserts](../)
* 라이브러리 [Aspose.Slides](../../)