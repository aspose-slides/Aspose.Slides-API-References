---
title: Print()
second_title: Aspose.Slides for C++ API 참조
description: 디버그 인터페이스에 메시지를 출력합니다.
type: docs
weight: 79
url: /ko/system.diagnostics/debug/print/
---
## Debug::Print(const String\&) 메서드

디버그 인터페이스에 메시지를 출력합니다.

```cpp
static void System::Diagnostics::Debug::Print(const String &message)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| message | const [String](../../../system/string/)\& | 작성할 메시지. |

## Debug::Print(const String\&, const System::ArrayPtr\<SharedPtr\<System::Object\>\>\&) 메서드

디버그 인터페이스에 메시지를 출력합니다.

```cpp
static void System::Diagnostics::Debug::Print(const String &format, const System::ArrayPtr<SharedPtr<System::Object>> &args)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | 형식 문자열. |
| args | const [System::ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\>\& | 형식 문자열에 대입할 인수. |

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Object](../../../system/object/)
* Struct [Debug](../)
* 네임스페이스 [System::Diagnostics](../../)
* Library [Aspose.Slides](../../../)