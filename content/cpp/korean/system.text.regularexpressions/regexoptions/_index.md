---
title: RegexOptions
second_title: Aspose.Slides for C++ API 레퍼런스
description: 정규식 옵션.
type: docs
weight: 118
url: /ko/system.text.regularexpressions/regexoptions/
---
## RegexOptions 열거형


[Regex](../regex/) 옵션.

```cpp
enum class RegexOptions
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | 0 | 기본 동작. |
| Compiled | 1 | 성능을 위해 regex를 컴파일합니다. 기본적으로 항상 수행됩니다. |
| CultureInvariant | 2 | 문화에 구애받지 않는 매칭을 사용합니다. 무시됩니다. |
| ECMAScript | 4 | ECMAScript 구문을 사용합니다. 무시됩니다. |
| ExplicitCapture | 8 | 명시적 캡처만 사용합니다. 무시됩니다. |
| IgnoreCase | 16 | 매칭 시 대소문자를 무시합니다. |
| IgnorePatternWhitespace | 32 | 패턴의 공백을 무시합니다. 지원되지 않음. |
| Multiline | 64 | '^'와 '$'를 문자열 전체가 아닌 한 줄의 시작과 끝으로 취급합니다. |
| RightToLeft | 128 | Right-to-left 매칭. 지원되지 않음. |
| Singleline | 256 | '.'가 예외 없이 모든 문자를 매치하도록 합니다 (일반적으로 개행 문자는 매치되지 않음). |

## 참고

* 네임스페이스 [System::Text::RegularExpressions](../)
* 라이브러리 [Aspose.Slides](../../)