---
title: AsyncCompletedEventArgs()
second_title: Справочник API Aspose.Slides для C++
description: Конструктор.
type: docs
weight: 1
url: /ru/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() конструктор

Конструктор.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) конструктор

Инициализирует новый экземпляр класса [System.ComponentModel.AsyncCompletedEventArgs](../).

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | Любая ошибка, произошедшая во время асинхронной операции. |
| canceled | **bool** | Значение, указывающее, была ли асинхронная операция отменена. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Необязательный пользовательский объект состояния, передаваемый методу [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |

## См. также

* typedef [Exception](../../../system/exception/)
* typedef [SharedPtr](../../../system/sharedptr/)
* Класс [AsyncCompletedEventArgs](../)
* Класс [Object](../../../system/object/)
* Пространство имён [System::ComponentModel](../../)
* Библиотека [Aspose.Slides](../../../)