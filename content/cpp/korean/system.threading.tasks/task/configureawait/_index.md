---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 작업에 대한 await가 컨텍스트 캡처와 관련하여 어떻게 동작해야 하는지를 구성합니다.
type: docs
weight: 144
url: /ko/system.threading.tasks/task/configureawait/
---
## Task::ConfigureAwait(bool) const 메서드

이 작업에 대한 await가 컨텍스트 캡처와 관련하여 어떻게 동작해야 하는지를 구성합니다.

```cpp
Runtime::CompilerServices::ConfiguredTaskAwaitable System::Threading::Tasks::Task::ConfigureAwait(bool continueOnCapturedContext) const
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | 캡처된 컨텍스트에서 계속할지 여부 |

### 반환값

[Runtime::CompilerServices::ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/) 구성된 awaitable

## 참조

* 클래스 [ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/)
* 클래스 [Task](../)
* 네임스페이스 [System::Threading::Tasks](../../)
* 라이브러리 [Aspose.Slides](../../../)