---
title: "System::Threading::Tasks"
second_title: "Aspose.Slides for C++ API 레퍼런스"
description: 
type: docs
weight: 1015
url: /ko/system.threading.tasks/
---
## 클래스

| 클래스 | 설명 |
| --- | --- |
| [Parallel](./parallel/) | 병렬 루프와 영역에 대한 지원을 제공합니다. |
| [ParallelLoopResult](./parallelloopresult/) | [Parallel](./parallel/) 루프의 완료 상태를 제공합니다. |
| [ParallelOptions](./paralleloptions/) | [Parallel](./parallel/) 클래스의 메서드 동작을 구성하는 옵션을 저장합니다. |
| [ResultTask](./resulttask/) | 완료 시 결과 값을 반환하는 [Task](./task/) 특수화입니다. |
| [ResultValueTask](./resultvaluetask/) | 직접 결과 값 또는 ResultTask<T>를 래핑할 수 있는 하이브리드 작업 유사 유형을 나타냅니다. |
| [Task](./task/) | 대기하고 다른 작업과 조합할 수 있는 비동기 작업을 나타냅니다. |
| [TaskScheduler](./taskscheduler/) | 작업을 스레드에 대기열에 넣는 저수준 작업을 처리하는 객체를 나타냅니다. |
| [ValueTask](./valuetask/) | 비동기 작업의 대기 가능한 결과를 제공합니다. |

## 함수

| 함수 | 설명 |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | 시간 지연 후에 완료되는 작업을 생성합니다. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | 시간 지연 후에 완료되고 취소될 수 있는 작업을 생성합니다. |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | 지정된 토큰으로 취소되어 완료된 작업을 생성합니다. |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | 지정된 예외와 함께 완료된 작업을 생성합니다. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | 지정된 예외 및 결과 형식과 함께 완료된 작업을 생성합니다. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | 지정된 결과와 함께 성공적으로 완료된 작업을 생성합니다. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | 지정된 작업을 스레드 풀에서 실행하도록 대기열에 넣고 해당 작업에 대한 [Task](./task/) 핸들을 반환합니다. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | 지정된 작업을 스레드 풀에서 실행하도록 대기열에 넣고 해당 작업에 대한 [Task](./task/) 핸들을 반환합니다. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | 지정된 작업을 스레드 풀에서 실행하도록 대기열에 넣고 함수가 반환하는 [Task](./task/)에 대한 프록시를 반환합니다. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | 지정된 작업을 스레드 풀에서 실행하도록 대기열에 넣고 해당 작업에 대한 Task<TResult> 핸들을 반환합니다. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | 제공된 모든 [Task](./task/) 객체가 실행을 완료할 때까지 대기합니다. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | 제공된 모든 [Task](./task/) 객체가 실행을 완료할 때까지 대기합니다. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | 제공된 [Task](./task/) 객체 중 하나가 실행을 완료할 때까지 대기합니다. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | 제공된 [Task](./task/) 객체 중 하나가 실행을 완료할 때까지 대기합니다. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | 제공된 모든 작업이 완료될 때 완료되는 작업을 생성합니다. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | 제공된 모든 작업이 완료될 때 완료되는 작업을 생성합니다. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | 제공된 모든 작업이 완료될 때 완료되는 작업을 생성합니다. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | 제공된 모든 작업이 완료될 때 완료되는 작업을 생성합니다. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | 제공된 작업 중 하나가 완료될 때 완료되는 작업을 생성합니다. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | 제공된 작업 중 하나가 완료될 때 완료되는 작업을 생성합니다. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | 제공된 작업 중 하나가 완료될 때 완료되는 작업을 생성합니다. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | 제공된 작업 중 하나가 완료될 때 완료되는 작업을 생성합니다. |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | 대기될 때 현재 컨텍스트로 비동기적으로 반환되는 대기 가능한 작업을 생성합니다. |

## 열거형

| 열거형 | 설명 |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |