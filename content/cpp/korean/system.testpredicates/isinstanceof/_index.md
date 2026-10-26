---
title: IsInstanceOf()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Is-instance-of는 IsInstanceOf 어설션 변환을 위한 인수를 비교합니다.
type: docs
weight: 118
url: /ko/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) 함수


Is-instance-of는 IsInstanceOf 어설션 변환을 위한 인수를 비교합니다.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 인수 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | 좌변 식. |
| rhs_expr | const char * | 우변 식. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | typeInfo 객체는 **obj**의 유형을 비교할 대상 유형을 나타냅니다 |
| obj | const T\& | 지정된 유형과 비교할 객체의 유형 |

### 반환 값

gtest-styled 어설션 결과.

## 또 보기

* 클래스 [TypeInfo](../../system/typeinfo/)
* 네임스페이스 [System::TestPredicates](../)
* 라이브러리 [Aspose.Slides](../../)