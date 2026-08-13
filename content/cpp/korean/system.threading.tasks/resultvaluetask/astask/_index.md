---
title: AsTask()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 ResultValueTask를 ResultTask<T>에 대한 공유 포인터로 변환합니다.
type: docs
weight: 79
url: /ko/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const 메서드

이 [ResultValueTask](../)를 ResultTask<T>에 대한 공유 포인터로 변환합니다.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```

### 반환 값

RTaskPtr<T> 이 작업을 나타내는 ResultTask<T>에 대한 공유 포인터입니다.

## 비고

[ResultValueTask](../)에 직접 결과가 포함된 경우 해당 결과로 완료된 작업을 생성합니다. 작업이 포함된 경우 해당 작업에 대한 공유 포인터를 반환합니다.

## 참조

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)