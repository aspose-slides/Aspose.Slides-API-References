---
title: FromException()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 예외와 함께 완료된 작업을 생성합니다.
type: docs
weight: 131
url: /ko/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) function


지정된 예외와 함께 완료된 작업을 생성합니다.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | 작업을 완료하는 데 사용되는 예외입니다. |

### Return Value

결함이 있는 작업.

## System::Threading::Tasks::FromException(const Exception\&) function


지정된 예외와 결과 유형과 함께 완료된 작업을 생성합니다.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TResult | 작업 결과의 유형입니다. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | 작업을 완료하는 데 사용되는 예외입니다. |

### Return Value

지정된 결과 유형을 가진 결함이 있는 작업.

## See Also

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* 네임스페이스 [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)