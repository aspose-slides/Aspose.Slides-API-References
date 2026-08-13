---
title: GetAwaiter()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 결과 작업에 대해 Await와 함께 사용할 awaiter를 가져옵니다.
type: docs
weight: 53
url: /ko/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const 메서드

이 결과 태스크에 대해 Await와 함께 사용할 awaiter를 가져옵니다.

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```

### 반환값

Runtime::CompilerServices::ResultTaskAwaiter<T> 결과를 반환하는 awaiter 인스턴스

## 비고

awaited 될 때, 코루틴은 결과 값이 사용 가능하도록 재개됩니다.

## 참조

* 클래스 [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* 클래스 [ResultTask](../)
* 네임스페이스 [System::Threading::Tasks](../../)
* 라이브러리 [Aspose.Slides](../../../)