---
title: AreBoxedValuesEqual()
second_title: Aspose.Slides C++ API 레퍼런스
description: 두 Boxed 타입을 동일하게 비교합니다.
type: docs
weight: 79
url: /ko/system.testpredicates.details.sharedptrasserts/areboxedvaluesequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreBoxedValuesEqual(const char *, const char *, const SharedPtr\<BoxedValueBase\>\&, const SharedPtr\<BoxedValueBase\>\&) 함수


두 Boxed 타입을 동일한지 비교합니다.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreBoxedValuesEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<BoxedValueBase> &lhs, const SharedPtr<BoxedValueBase> &rhs)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 식. |
| rhs_expr | const char * | RHS 식. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[BoxedValueBase](../../system/boxedvaluebase/)\>\& | LHS 값. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[BoxedValueBase](../../system/boxedvaluebase/)\>\& | RHS 값. |

### 반환 값

gtest 스타일의 어설션 결과.

## 참조

* Typedef [SharedPtr](../../system/sharedptr/)
* 클래스 [BoxedValueBase](../../system/boxedvaluebase/)
* 네임스페이스 [System::TestPredicates::Details::SharedPtrAsserts](../)
* 라이브러리 [Aspose.Slides](../../)