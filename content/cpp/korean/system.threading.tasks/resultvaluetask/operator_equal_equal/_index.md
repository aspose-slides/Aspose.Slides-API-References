---
title: operator==()
second_title: Aspose.Slides for C++ API 레퍼런스
description: ResultValueTask에 대한 등호 연산자.
type: docs
weight: 131
url: /ko/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const method

[ResultValueTask](../)에 대한 등호 연산자.

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | 이 인스턴스와 비교할 다른 [ResultValueTask](../). |

### 반환값

bool 두 작업이 동일한 결과 값을 가지고 있거나 동일한 기본 작업을 참조하면 true; 그렇지 않으면 false.

## 비고

인스턴스 중 하나에 직접 결과 값이 포함되어 있으면 결과를 직접 비교합니다. 그렇지 않으면 기본 작업 포인터를 비교합니다.

## 참조

* 클래스 [ResultValueTask](../)
* 네임스페이스 [System::Threading::Tasks](../../)
* 라이브러리 [Aspose.Slides](../../../)