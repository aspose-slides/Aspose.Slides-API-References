---
title: TryParse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자열을 bool 타입의 값으로 변환합니다.
type: docs
weight: 14
url: /ko/system/boolean/tryparse/
---
## Boolean::TryParse(const String\&, bool\&) 메서드

지정된 문자열을 bool 유형의 값으로 변환합니다.

```cpp
static bool System::Boolean::TryParse(const String &value, bool &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열입니다. |
| result | **bool**\& | 변환 결과가 저장되는 bool 변수에 대한 참조입니다; 지정된 문자열이 \"True\"와 같으면 결과는 true이며, 지정된 문자열이 \"False\"와 같으면 결과는 false입니다. |

### 반환 값

지정된 문자열이 \"True\" 또는 \"False\"와 같으면 true이며, 그렇지 않으면 false입니다.

## 관련 항목

* 클래스 [String](../../string/)
* 클래스 [Boolean](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)