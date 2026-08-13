---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 작업에 대한 awaiter를 구성합니다.
type: docs
weight: 79
url: /ko/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait(bool) const 메서드


이 작업에 대한 awaiter를 구성합니다.

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true인 경우 캡처된 원본 컨텍스트로 이어짐을 다시 전달하려고 시도합니다; false인 경우 그렇지 않습니다. |

### 반환 값

ConfiguredValueTaskAwaitable 이 작업에 대한 awaiter 동작을 구성하는 객체.

## 참조

* 클래스 [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* 클래스 [ValueTask](../)
* 네임스페이스 [System::Threading::Tasks](../../)
* 라이브러리 [Aspose.Slides](../../../)