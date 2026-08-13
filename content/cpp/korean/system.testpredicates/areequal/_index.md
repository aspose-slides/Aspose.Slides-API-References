---
title: AreEqual()
second_title: Aspose.Slides for C++ API 레퍼런스
description: AreEqual 단언 변환을 위해 인수를 동등 비교합니다.
type: docs
weight: 14
url: /ko/system.testpredicates/areequal/
---
## System::TestPredicates::AreEqual(const char *, const char *, T1\&&, T2\&&) function

Equal은 AreEqual 단언 변환을 위해 인수를 비교합니다.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 객체 유형. |
| T2 | RHS 객체 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 표현식. |
| rhs_expr | const char * | RHS 표현식. |
| lhs | T1\&& | LHS 값. |
| rhs | T2\&& | RHS 값. |

### 반환 값

gtest 스타일의 단언 결과.

## 참조

* 네임스페이스 [System::TestPredicates](../)
* 라이브러리 [Aspose.Slides](../../)