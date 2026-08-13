---
title: Assert()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 조건을 검증하고 실패 시 정보를 전송합니다.
type: docs
weight: 14
url: /ko/system.diagnostics/debug/assert/
---
## Debug::Assert(bool) 메서드

조건을 검증하고 실패 시 정보를 전송합니다.

```cpp
static void System::Diagnostics::Debug::Assert(bool condition)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| condition | **bool** | Condition value. |

## Debug::Assert(bool, const String\&) 메서드

조건을 검증하고 실패 시 정보를 전송합니다.

```cpp
static void System::Diagnostics::Debug::Assert(bool condition, const String &message)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| condition | **bool** | Condition value. |
| message | const [String](../../../system/string/)\& | Message to populate on assertion failure. |

## Debug::Assert(bool, const char *) 메서드

조건을 검증하고 실패 시 정보를 전송합니다.

```cpp
static void System::Diagnostics::Debug::Assert(bool condition, const char *message)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| condition | **bool** | Condition value. |
| message | const char * | Message to populate on assertion failure. |

## Debug::Assert(bool, const String\&, const String\&) 메서드

조건을 검증하고 실패 시 정보를 전송합니다.

```cpp
static void System::Diagnostics::Debug::Assert(bool condition, const String &message, const String &detailMessage)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| condition | **bool** | Condition value. |
| message | const [String](../../../system/string/)\& | Message to populate on assertion failure. |
| detailMessage | const [String](../../../system/string/)\& | Detailed message to populate on assertion failure. |

## 참고

* 클래스 [String](../../../system/string/)
* 구조체 [Debug](../)
* 네임스페이스 [System::Diagnostics](../../)
* 라이브러리 [Aspose.Slides](../../../)