---
title: SpecifyKind()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 DateTime 객체와 동일한 틱 수를 나타내며, 인수 kind에 따라 로컬 시간, UTC 시간 또는 그 어느 것도 아닌 시간을 나타내는 새 DateTime 객체를 생성합니다.
type: docs
weight: 833
url: /ko/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) 메서드

지정된 [DateTime](../) 객체와 동일한 틱 수를 나타내며, 인수 **kind**에 따라 로컬 시간, UTC 시간 또는 그 어느 것도 아닌 시간을 나타내는 새 [DateTime](../) 객체를 생성합니다.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DateTime](../) | [DateTime](../) 객체에서 틱 수를 복사하는 대상 |
| kind | [DateTimeKind](../../datetimekind/) | 새 객체가 로컬 시간, UTC 시간 또는 그 어느 것도 아닌 시간을 나타낼지 지정합니다. |

### 반환값

새 [DateTime](../) 객체로, **value**와 **kind**에 지정된 DateTimeKind 값과 동일한 틱 수를 나타냅니다.

## 참조

* 열거형 [DateTimeKind](../../datetimekind/)
* 클래스 [DateTime](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)