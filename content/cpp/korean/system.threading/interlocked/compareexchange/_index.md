---
title: CompareExchange()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "변수의 값을 원자적으로 교환합니다: 변수가 특정 값과 같은지 확인하고, 저장된 값이 기대값과 일치할 경우에만 새 값을 저장합니다."
type: docs
weight: 79
url: /ko/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(T\&, T, T) method

변수의 값을 원자적으로 교환합니다: 변수가 특정 값과 같은지 확인하고, 저장된 값이 기대값과 일치할 경우에만 새 값을 저장합니다.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | 변수 형식. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| location1 | T\& | 변경할 변수 참조. |
| value | T | 저장할 값. |
| comparand | T | 교환하기 전에 변수의 값과 비교할 값. |

### Return Value

연산 시작 시 변수의 값으로, 변경 여부와 관계없이 반환됩니다.

## Interlocked::CompareExchange(T\&, T, T) method

변수의 값을 원자적으로 교환합니다: 변수가 특정 값과 같은지 확인하고, 저장된 값이 기대값과 일치할 경우에만 새 값을 저장합니다. 구현되지 않음.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | 변수 형식. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| location1 | T\& | 변경할 변수 참조. |
| value | T | 저장할 값. |
| comparand | T | 교환하기 전에 변수의 값과 비교할 값. |

### Return Value

연산 시작 시 변수의 값으로, 변경 여부와 관계없이 반환됩니다.

## Interlocked::CompareExchange(int32_t\&, int32_t, int32_t, bool\&) method

변수의 값을 원자적으로 교환합니다: 변수가 특정 값과 같은지 확인하고, 저장된 값이 기대값과 일치할 경우에만 새 값을 저장합니다.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| location1 | **int32_t**\& | 변경할 변수 참조. |
| value | **int32_t** | 저장할 값. |
| comparand | **int32_t** | 교환하기 전에 변수의 값과 비교할 값. |
| succeeded | **bool**\& | 교환이 발생하면 true, 그렇지 않으면 false가 설정되는 변수의 참조. |

### Return Value

연산 시작 시 변수의 값으로, 변경 여부와 관계없이 반환됩니다.

## See Also

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)