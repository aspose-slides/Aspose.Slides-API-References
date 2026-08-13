---
title: NotEqFailure()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 출력에 대한 != 어설션 실패를 포맷합니다.
type: docs
weight: 40
url: /ko/system.testpredicates.details/noteqfailure/
---
## System::TestPredicates::Details::NotEqFailure(const char *, const char *, T1\&, T2\&) 함수

출력에 대한 != 어설션 실패를 포맷합니다.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotEqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 값 타입. |
| T2 | RHS 값 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | T1\& | LHS 값. |
| rhs | T2\& | RHS 값. |

### 반환 값

[Object](../../system/object/) 실패 텍스트를 래핑합니다.

## 참고

* 네임스페이스 [System::TestPredicates::Details](../)
* 라이브러리 [Aspose.Slides](../../)