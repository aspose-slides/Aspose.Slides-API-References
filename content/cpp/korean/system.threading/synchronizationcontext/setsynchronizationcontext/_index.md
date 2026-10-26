---
title: SetSynchronizationContext()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 스레드에 대한 동기화 컨텍스트를 설정합니다.
type: docs
weight: 53
url: /ko/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) 메서드

현재 스레드에 대한 동기화 컨텍스트를 설정합니다.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | 현재 스레드에 설정할 동기화 컨텍스트입니다. |
## 비고

nullptr를 전달하면 현재 스레드에 대한 동기화 컨텍스트가 지워집니다. 

## 관련 항목

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [SynchronizationContext](../)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)