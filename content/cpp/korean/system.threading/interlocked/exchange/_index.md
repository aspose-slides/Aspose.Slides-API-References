---
title: Exchange()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "변수의 값을 교환합니다: 새 값을 저장하고 저장하기 직전에 변수에 있던 값을 반환합니다."
type: docs
weight: 66
url: /ko/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) 메서드


변수의 값을 교환합니다: 새 값을 저장하고 저장하기 직전에 변수에 있던 값을 반환합니다.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 변수 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| location1 | T\& | 변경할 변수 참조. |
| value | T | 저장할 값. |

### 반환 값

변경되기 직전 변수의 값.

## Interlocked::Exchange(T\&, T) 메서드


변수의 값을 교환합니다: 새 값을 저장하고 저장하기 직전에 변수에 있던 값을 반환합니다. 구현되지 않음.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 변수 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| location1 | T\& | 변경할 변수 참조. |
| value | T | 저장할 값. |

### 반환 값

변경되기 직전 변수의 값.

## 또 보기

* 클래스 [Interlocked](../)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)