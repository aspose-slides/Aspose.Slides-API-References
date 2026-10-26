---
title: QueueUserWorkItem()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 콜백에 매개변수가 없는 작업 항목을 큐에 삽입합니다.
type: docs
weight: 14
url: /ko/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) 메서드

콜백이 매개변수가 없는 작업 항목을 큐에 삽입합니다.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | 작업으로 사용할 콜백 함수입니다. |

### 반환 값

항상 true를 반환합니다.

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) 메서드

콜백이 매개변수가 없는 작업 항목을 큐에 삽입합니다.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | 작업으로 사용할 콜백 함수입니다. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 작업 함수 매개변수입니다. |

### 반환 값

항상 true를 반환합니다.

## 관련 항목

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ThreadPool](../)
* 클래스 [Object](../../../system/object/)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)