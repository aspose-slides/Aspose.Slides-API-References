---
title: ThreadPoolImpl
second_title: Aspose.Slides for C++ API 레퍼런스
description: 스레드 풀 내부 데이터. 이는 접근 함수에 의해 메모리 관리가 이루어지는 싱글톤 타입입니다. 직접 인스턴스를 생성하면 안 됩니다.
type: docs
weight: 235
url: /ko/system.threading/threadpoolimpl/
---
## ThreadPoolImpl 클래스


[Thread](../thread/) pool internal data. This is a singleton type with memory management done by access function(s). You should never create instances of it directly.

```cpp
class ThreadPoolImpl
```

## 메서드

| Method | Description |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | 사용 가능한 스레드 수를 가져옵니다. |
| static **bool**\& [GetInitialized](./getinitialized/)() | 초기화 상태 싱글톤을 가져옵니다. |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | 동시 실행 가능한 최대 스레드 수를 가져옵니다. |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | 풀에서 생성되는 최소 스레드 수를 가져옵니다. |
| void [JoinAll](./joinall/)() | 모든 소유 스레드에 조인합니다. 무한히 대기합니다. |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | 작업 항목을 큐에 추가합니다. |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | 풀에 소유된 스레드 수를 설정합니다. |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | 풀에 소유된 최소 스레드 수를 설정합니다. |
|  [ThreadPoolImpl](./threadpoolimpl/)() | 생성자. |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | 소멸자. 아직 종료되지 않은 경우 모든 스레드에 조인합니다. |
## 참고

* 네임스페이스 [System::Threading](../)
* 라이브러리 [Aspose.Slides](../../)