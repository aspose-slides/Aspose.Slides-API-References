---
title: QueueUserWorkItem()
second_title: Aspose.Slides for C++ API 참조
description: 작업 항목을 큐에 추가합니다.
type: docs
weight: 1
url: /ko/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) 메서드

작업 항목을 큐에 추가합니다.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | 실행할 콜백 함수. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 콜백 함수 인자. |

### 반환 값

항상 true를 반환합니다.

## 참고

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [ThreadPoolImpl](../)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)