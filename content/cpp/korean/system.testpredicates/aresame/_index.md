---
title: AreSame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: AreSame 어설션 번역을 위한 인수를 비교합니다.
type: docs
weight: 66
url: /ko/system.testpredicates/aresame/
---
## System::TestPredicates::AreSame(const char *, const char *, const T1\&, const T2\&) function

AreSame 어설션을 위한 인수를 비교합니다.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 좌변 객체 유형. |
| T2 | 우변 객체 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 식. |
| rhs_expr | const char * | 우변 식. |
| lhs | const T1\& | 좌변 값. |
| rhs | const T2\& | 우변 값. |

### 반환 값

gtest 스타일의 어설션 결과.

## 참조

* 네임스페이스 [System::TestPredicates](../)
* 라이브러리 [Aspose.Slides](../../)