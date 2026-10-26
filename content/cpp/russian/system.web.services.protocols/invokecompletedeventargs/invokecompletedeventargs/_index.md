---
title: InvokeCompletedEventArgs()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый экземпляр.
type: docs
weight: 14
url: /ru/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) конструктор

Создаёт новый экземпляр.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | Любая ошибка, возникшая во время асинхронной операции. |
| cancelled | **bool** | Значение, указывающее, отменена ли асинхронная операция. |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Необязательный объект состояния, предоставленный пользователем, передаваемый в метод [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Коллекция результатов асинхронной операции. |

## См. также

* Тип [Exception](../../../system/exception/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [Object](../../../system/object/)
* Класс [InvokeCompletedEventArgs](../)
* Пространство имён [System::Web::Services::Protocols](../../)
* Библиотека [Aspose.Slides](../../../)