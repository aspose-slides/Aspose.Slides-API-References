---
title: SameFailure()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 출력용 'same' 어설션 실패를 형식화합니다.
type: docs
weight: 53
url: /ko/system.testpredicates.details/samefailure/
---
## System::TestPredicates::Details::SameFailure(const char *, const char *, T1\&, T2\&) 함수

출력에 사용되는 'same' 어설션 실패 메시지를 형식화합니다.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | LHS 값 타입. |
| T2 | RHS 값 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | 좌변(LHS) 표현식. |
| rhs_expr | const char * | 우변(RHS) 표현식. |
| lhs | T1\& | 좌변 값. |
| rhs | T2\& | 우변 값. |

### 반환 값

[Object](../../system/object/) 래핑된 실패 텍스트.

## 참조

* 네임스페이스 [System::TestPredicates::Details](../)
* 라이브러리 [Aspose.Slides](../../)