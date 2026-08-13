---
title: TryParse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자열을 동등한 열거형 상수로 변환하려고 시도합니다.
type: docs
weight: 79
url: /ko/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) 메서드

지정된 문자열을 동등한 열거형 상수로 변환하려고 시도합니다.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/)은(는) 열거형 상수 이름을 포함하고 있는 것으로 해석됩니다 |
| result | E\& | 변환이 성공하면 변환 결과를 포함하는 출력 매개변수 |

### 반환 값

변환에 성공하면 true, 그렇지 않으면 false

## Enum::TryParse(const String\&, bool, E\&) 메서드

지정된 문자열을 동등한 열거형 상수로 변환하려고 시도합니다.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/)은(는) 열거형 상수 이름을 포함하고 있는 것으로 해석됩니다 |
| ignoreCase | **bool** | 문자열을 해석할 때 대소문자를 무시할지 여부를 지정합니다 |
| result | E\& | 변환이 성공하면 함수 반환 시 변환 결과를 포함하는 출력 매개변수 |

### 반환 값

변환에 성공하면 true, 그렇지 않으면 false

## 참고

* 클래스 [String](../../string/)
* 구조체 [Enum](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)