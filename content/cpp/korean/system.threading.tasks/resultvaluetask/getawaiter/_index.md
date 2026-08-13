---
title: GetAwaiter()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 작업에 대한 awaiter를 가져와 await 식을 지원합니다.
type: docs
weight: 118
url: /ko/system.threading.tasks/resultvaluetask/getawaiter/
---
## ResultValueTask::GetAwaiter() const 메서드

Gets an awaiter for this task to support await expressions.

```cpp
Runtime::CompilerServices::ResultValueTaskAwaiter<T> System::Threading::Tasks::ResultValueTask<T>::GetAwaiter() const
```

### 반환 값

ResultValueTaskAwaiter<T> 이 작업에 대한 awaiter 인스턴스.
## 비고

이 메서드는 [ResultValueTask](../)와 함께 Await 메서드 사용을 가능하게 합니다.

## 참조

* 클래스 [ResultValueTaskAwaiter](../../../system.runtime.compilerservices/resultvaluetaskawaiter/)
* 클래스 [ResultValueTask](../)
* 네임스페이스 [System::Threading::Tasks](../../)
* 라이브러리 [Aspose.Slides](../../../)