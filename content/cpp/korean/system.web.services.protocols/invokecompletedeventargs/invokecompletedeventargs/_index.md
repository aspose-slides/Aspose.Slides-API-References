---
title: InvokeCompletedEventArgs()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 인스턴스를 생성합니다.
type: docs
weight: 14
url: /ko/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) constructor

새 인스턴스를 생성합니다.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | 비동기 작업 중에 발생한 모든 오류입니다. |
| cancelled | **bool** | 비동기 작업이 취소되었는지 여부를 나타내는 값입니다. |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 선택적인 사용자 제공 상태 객체로, [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) 메서드에 전달됩니다. |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | 비동기 작업 결과의 컬렉션입니다. |

## 관련 정보

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [InvokeCompletedEventArgs](../)
* 네임스페이스 [System::Web::Services::Protocols](../../)
* 라이브러리 [Aspose.Slides](../../../)