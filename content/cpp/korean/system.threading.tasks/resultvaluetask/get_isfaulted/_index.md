---
title: get_IsFaulted()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 작업이 처리되지 않은 예외로 인해 완료되었는지 여부를 나타내는 값을 가져옵니다.
type: docs
weight: 14
url: /ko/system.threading.tasks/resultvaluetask/get_isfaulted/
---
## ResultValueTask::get_IsFaulted() const 메서드

Gets a value indicating whether the task completed due to an unhandled exception.

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::get_IsFaulted() const
```

### 반환 값

bool True 작업이 오류가 발생한 경우; 그렇지 않으면 false.

## 비고

작업에 직접 결과 값이 포함된 경우 false를 반환합니다.

## 참고

* 클래스 [ResultValueTask](../)
* 네임스페이스 [System::Threading::Tasks](../../)
* 라이브러리 [Aspose.Slides](../../../)