---
title: AreNotSame()
second_title: Aspose.Slides for C++ API 참조
description: Are-not-same는 AreSame 단언 번역을 위한 인수를 비교합니다.
type: docs
weight: 92
url: /ko/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1&, const T2&) 함수

Are-not-same-compares는 AreSame 단언 번역을 위한 인수입니다.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |

### 반환값

gtest 기반 단언 결과.

## 참고

* 네임스페이스 [System::TestPredicates](../)
* 라이브러리 [Aspose.Slides](../../)