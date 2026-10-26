---
title: Next()
second_title: Aspose.Slides for C++ API 레퍼런스
description: int32 최대값보다 작고 음수가 아닌 무작위 숫자를 반환합니다.
type: docs
weight: 27
url: /ko/system/random/next/
---
## Random::Next() 메서드

int32 최대값보다 작고 음수가 아닌 무작위 숫자를 반환합니다.

```cpp
virtual int32_t System::Random::Next()
```

## Random::Next(int32_t) 메서드

지정된 최대값보다 작고 음수가 아닌 무작위 숫자를 반환합니다.

```cpp
virtual int32_t System::Random::Next(int32_t maxValue)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| maxValue | **int32_t** | 메서드에 의해 생성되는 값은 이 값보다 작습니다 |

## Random::Next(int32_t, int32_t) 메서드

지정된 범위 내에서 무작위 숫자를 반환합니다.

```cpp
virtual int32_t System::Random::Next(int32_t minValue, int32_t maxValue)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| minValue | **int32_t** | 메서드에 의해 생성되는 값은 이 값보다 큽니다 |
| maxValue | **int32_t** | 메서드에 의해 생성되는 값은 이 값보다 작습니다 |

## 참조

* 클래스 [Random](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)