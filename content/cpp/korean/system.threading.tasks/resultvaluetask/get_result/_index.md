---
title: get_Result()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 완료된 작업의 결과를 가져옵니다.
type: docs
weight: 66
url: /ko/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() 메서드

완료된 작업의 결과를 가져옵니다.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```

### 반환 값

T 결과 값.
## 비고

작업이 ResultTask<T>에 의해 지원되는 경우, 이 메서드는 결과를 기다렸다가 캐시합니다. 이후 호출은 대기 없이 캐시된 값을 반환합니다.

## 또 보기

* 클래스 [ResultValueTask](../)
* 네임스페이스 [System::Threading::Tasks](../../)
* 라이브러리 [Aspose.Slides](../../../)