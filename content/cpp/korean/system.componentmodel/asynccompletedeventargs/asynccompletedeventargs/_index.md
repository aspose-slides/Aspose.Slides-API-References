---
title: AsyncCompletedEventArgs()
second_title: Aspose.Slides for C++ API 참조
description: 생성자.
type: docs
weight: 1
url: /ko/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() 생성자


생성자.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) 생성자


새 [System.ComponentModel.AsyncCompletedEventArgs](../) 클래스의 인스턴스를 초기화합니다.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | 비동기 작업 중 발생한 모든 오류. |
| canceled | **bool** | 비동기 작업이 취소되었는지 여부를 나타내는 값. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) 메서드에 전달된 선택적 사용자 제공 상태 객체. |

## 관련 항목

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [AsyncCompletedEventArgs](../)
* 클래스 [Object](../../../system/object/)
* 네임스페이스 [System::ComponentModel](../../)
* 라이브러리 [Aspose.Slides](../../../)