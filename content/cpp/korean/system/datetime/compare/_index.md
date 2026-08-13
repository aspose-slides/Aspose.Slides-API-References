---
title: Compare()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 DateTime 클래스 인스턴스로 표현된 두 값을 비교하고, 시간 축에서 값들의 상대적 위치를 나타내는 값을 반환합니다.
type: docs
weight: 846
url: /ko/system/datetime/compare/
---
## DateTime::Compare(DateTime, DateTime) 메서드

지정된 [DateTime](../) 클래스 인스턴스로 표현된 두 값을 비교하고, 시간 축에서 값들의 상대적 위치를 나타내는 값을 반환합니다.

```cpp
static constexpr int System::DateTime::Compare(DateTime t1, DateTime t2)
```

### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| t1 | [DateTime](../) | 첫 번째 비교 대상 |
| t2 | [DateTime](../) | 두 번째 비교 대상 |

### 반환 값

**t1**이 **t2**보다 이전이면 0보다 작은 값, **t1**과 **t2**가 동일하면 0, **t1**이 **t2**보다 늦으면 0보다 큰 값을 반환합니다.

## 참조

* 클래스 [DateTime](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)