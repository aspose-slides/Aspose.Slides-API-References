---
title: operator=()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 복사 할당.
type: docs
weight: 27
url: /ko/system/func/operator_equal/
---
## Func::operator=(const Func\&) 메서드

복사 할당.

```cpp
Func & System::Func<Args>::operator=(const Func &other)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const [Func](../)\& | [Func](../) 현재 객체에 복사할 delegate. |

### 반환값

현재 객체에 대한 참조.

## Func::operator=(Func\&&) 메서드

이동 할당.

```cpp
Func & System::Func<Args>::operator=(Func &&other) noexcept
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [Func](../)\&& | [Func](../) 현재 객체로 이동할 delegate. 상태가 변경될 수 있습니다. |

### 반환값

현재 객체에 대한 참조.

## 참조

* 클래스 [Func](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)