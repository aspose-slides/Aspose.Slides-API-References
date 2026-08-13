---
title: RunWorkerAsync()
second_title: Aspose.Slides for C++ API 참조
description: 백그라운드 작업의 실행을 시작합니다.
type: docs
weight: 27
url: /ko/system.componentmodel/backgroundworker/runworkerasync/
---
## BackgroundWorker::RunWorkerAsync() 메서드


백그라운드 작업의 실행을 시작합니다.

```cpp
void System::ComponentModel::BackgroundWorker::RunWorkerAsync()
```

## BackgroundWorker::RunWorkerAsync(const System::SharedPtr\<System::Object\>\&) 메서드


백그라운드 작업의 실행을 시작합니다.

```cpp
void System::ComponentModel::BackgroundWorker::RunWorkerAsync(const System::SharedPtr<System::Object> &argument)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| argument | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 백그라운드 작업에서 사용되는 매개변수이며 **System::ComponentModel::BackgroundWorker::DoWork** 이벤트 핸들러에서 실행됩니다. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [BackgroundWorker](../)
* 클래스 [Object](../../../system/object/)
* 네임스페이스 [System::ComponentModel](../../)
* 라이브러리 [Aspose.Slides](../../../)