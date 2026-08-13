---
title: HasFlag()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 enum 값의 비트 배열 표현에서 지정된 비트가 설정되어 있는지 확인합니다.
type: docs
weight: 14
url: /ko/system/enum/hasflag/
---
## Enum::HasFlag(E, E) 메서드

지정된 enum 값의 비트 배열 표현에서 지정된 비트가 설정되어 있는지 확인합니다.

```cpp
static bool System::Enum<E, Guard>::HasFlag(E value, E mask)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | E | 테스트할 enum 값 |
| mask | E | value의 비트를 확인할 마스크 |

### 반환 값

**mask**에 설정된 비트가 **value**에도 설정되어 있으면 True, 그렇지 않으면 false

## 참고

* 구조체 [Enum](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)