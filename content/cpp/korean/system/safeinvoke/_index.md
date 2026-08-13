---
title: SafeInvoke()
second_title: Aspose.Slides for C++ API 레퍼런스
description: ‘?.’ 연산자 변환 구현.
type: docs
weight: 2653
url: /ko/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) 함수

Implementation of '?.' operator translation.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T0 | 식 유형. |
| T1 | ‘WhenTrue’ 식을 캡슐화하는 람다의 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| expr | T0\&& | 식 값. |
| func | T1\&& | ‘WhenTrue’ 식이 펀터에 바인드된 경우. |

### 반환 값

expr 값이 null이 아니면, 해당 값을 첫 번째 인수로 하여 func를 호출하고 그 결과를 반환합니다. 그렇지 않으면 null을 반환합니다.

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)