---
title: ReportProgress()
second_title: Aspose.Slides C++ API 레퍼런스
description: "System::ComponentModel::BackgroundWorker::ProgressChanged 이벤트를 발생시킵니다."
type: docs
weight: 40
url: /ko/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) 메서드

다음 **System::ComponentModel::BackgroundWorker::ProgressChanged** 이벤트를 발생시킵니다.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| percentProgress | int | 백그라운드 작업이 완료된 비율(0~100)입니다. |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) 메서드

다음 **System::ComponentModel::BackgroundWorker::ProgressChanged** 이벤트를 userState 객체와 함께 발생시킵니다.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| percentProgress | int | 백그라운드 작업이 완료된 비율(0~100)입니다. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object) 에 전달되는 상태 객체입니다. |

## 참고

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [BackgroundWorker](../)
* 클래스 [Object](../../../system/object/)
* 네임스페이스 [System::ComponentModel](../../)
* 라이브러리 [Aspose.Slides](../../../)