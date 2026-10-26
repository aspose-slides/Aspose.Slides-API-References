---
title: ConfigureAwait()
second_title: Aspose.Slides C++ API 레퍼런스
description: 이 작업에 대한 awaiter를 구성합니다.
type: docs
weight: 92
url: /ko/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const 메서드


이 작업에 대한 awaiter를 구성합니다.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


### Arguments

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true이면 캡처된 원래 컨텍스트로 이어짐을 다시 전달하려 시도하고, false이면 그렇지 않습니다. |

### 반환 값

ConfiguredResultValueTaskAwaitable<T> 이 작업에 대한 awaiter 동작을 구성하는 객체.

## 참고

* 클래스 [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* 클래스 [ResultValueTask](../)
* 네임스페이스 [System::Threading::Tasks](../../)
* 라이브러리 [Aspose.Slides](../../../)