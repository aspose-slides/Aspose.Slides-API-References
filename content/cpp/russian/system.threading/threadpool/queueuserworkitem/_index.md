---
title: QueueUserWorkItem()
second_title: Aspose.Slides для C++: справочник API
description: Помещает элемент работы в очередь, где указан обратный вызов без параметров.
type: docs
weight: 14
url: /ru/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) метод

Помещает элемент работы в очередь, в которой присутствует обратный вызов без параметров.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Функция обратного вызова, используемая как задача. |

### Return Value

Всегда возвращает true.

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) метод

Помещает элемент работы в очередь, в которой присутствует обратный вызов без параметров.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Функция обратного вызова, используемая как задача. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Параметр функции задачи. |

### Return Value

Всегда возвращает true.

## See Also

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ThreadPool](../)
* Класс [Object](../../../system/object/)
* Пространство имён [System::Threading](../../)
* Библиотека [Aspose.Slides](../../../)