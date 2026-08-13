---
title: Yield()
second_title: Aspose.Slides for C++ API 참조
description: 대기될 때 현재 컨텍스트로 비동기적으로 반환하는 대기 가능한 작업을 생성합니다.
type: docs
weight: 222
url: /ko/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() 함수


대기될 때 현재 컨텍스트로 비동기적으로 반환하는 대기 가능한 작업을 생성합니다.
```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```


### 반환값

제어를 양도하기 위해 대기할 수 있는 YieldAwaitable.
## 비고



이 메서드는 비동기 메서드가 제어권을 양도하도록 강제하여, 계속 진행하기 전에 다른 대기 중인 작업이 처리될 수 있도록 합니다. 
## 관련 항목

* 클래스 [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* 네임스페이스 [System::Threading::Tasks](../)
* 라이브러리 [Aspose.Slides](../../)