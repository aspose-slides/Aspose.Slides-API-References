---
title: ReportProgress()
second_title: Aspose.Slides для C++ API Reference
description: "Вызывает событие System::ComponentModel::BackgroundWorker::ProgressChanged."
type: docs
weight: 40
url: /ru/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) метод

Вызывает событие **System::ComponentModel::BackgroundWorker::ProgressChanged**.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| percentProgress | int | Процент от 0 до 100 выполнения фоновой операции. |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) метод

Вызывает событие **System::ComponentModel::BackgroundWorker::ProgressChanged** с объектом userState.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| percentProgress | int | Процент от 0 до 100 выполнения фоновой операции. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Объект состояния, передаваемый в System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object). |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [BackgroundWorker](../)
* Класс [Object](../../../system/object/)
* Пространство имён [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)