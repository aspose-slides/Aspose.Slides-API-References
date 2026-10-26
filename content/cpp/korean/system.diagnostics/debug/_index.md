---
title: Debug
second_title: Aspose.Slides for C++ API 레퍼런스
description: 등록된 리스너에게 디버그 정보를 전송할 수 있는 디버그 메서드 모음입니다. 모든 출력 함수는 Debug에서만 작동합니다. 이는 인스턴스를 갖지 않는 정적 타입이며, 어떤 방법으로도 인스턴스를 생성해서는 안 됩니다.
type: docs
weight: 105
url: /ko/system.diagnostics/debug/
---
## 디버그 구조체

등록된 리스너에게 디버그 정보를 전송할 수 있는 디버그 메서드 모음입니다. 모든 출력 함수는 [Debug](./)에서만 작동합니다. 이는 인스턴스를 갖지 않는 정적 타입이며, 어떤 방법으로도 인스턴스를 생성해서는 안 됩니다.

```cpp
class Debug
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | 조건을 검사하고 실패 시 정보를 전송합니다. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | 조건을 검사하고 실패 시 정보를 전송합니다. |
| static void [Assert](./assert/)(**bool**, const char *) | 조건을 검사하고 실패 시 정보를 전송합니다. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 조건을 검사하고 실패 시 정보를 전송합니다. |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | 실패 메시지를 전송합니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | 정적 리스너 목록에 접근합니다. |
| static void [Print](./print/)(const [String](../../system/string/)\&) | 디버그 인터페이스에 메시지를 출력합니다. |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | 디버그 인터페이스에 메시지를 출력합니다. |
| static void [Write](./write/)(const [String](../../system/string/)\&) | 디버그 인터페이스에 문자열을 씁니다. |
| static void [Write](./write/)(const char_t *) | 디버그 인터페이스에 문자열을 씁니다. |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | 조건이 true인 경우 디버그 인터페이스에 문자열을 씁니다. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | 디버그 인터페이스에 라인을 씁니다. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 디버그 인터페이스에 라인을 씁니다. |
| static void [WriteLine](./writeline/)(const char_t *) | 디버그 인터페이스에 라인을 씁니다. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 디버그 인터페이스에 라인을 씁니다. |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | 조건이 true인 경우 디버그 인터페이스에 라인을 씁니다. |

## 또한 보기

* 네임스페이스 [System::Diagnostics](../)
* 라이브러리 [Aspose.Slides](../../)