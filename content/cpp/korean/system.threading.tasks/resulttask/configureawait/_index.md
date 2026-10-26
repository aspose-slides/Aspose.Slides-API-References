---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API 참조
description: 이 결과 작업에 대한 await가 컨텍스트 캡처와 관련하여 어떻게 동작해야 하는지 구성합니다.
type: docs
weight: 27
url: /ko/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const 메서드

이 결과 작업에 대한 await 동작이 컨텍스트 캡처와 관련하여 어떻게 동작할지 구성합니다.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | 캡처된 컨텍스트에서 계속 실행할지 여부 |

### 반환값

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> 결과에 대한 구성된 awaitable

## 비고

이는 async/await 패턴에 대한 컨텍스트 흐름을 세밀하게 제어할 수 있게 합니다.

## 참고

* 클래스 [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* 클래스 [ResultTask](../)
* 네임스페이스 [System::Threading::Tasks](../../)
* 라이브러리 [Aspose.Slides](../../../)