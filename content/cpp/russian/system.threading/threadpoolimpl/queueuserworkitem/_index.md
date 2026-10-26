---
title: QueueUserWorkItem()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет элемент работы в очередь.
type: docs
weight: 1
url: /ru/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) method


Добавляет элемент работы в очередь.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Функция обратного вызова для выполнения. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Аргумент функции обратного вызова. |

### Возвращаемое значение

Всегда возвращает true.

## См. также

* Типовое определение [WaitCallback](../../waitcallback/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [ThreadPoolImpl](../)
* Пространство имён [System::Threading](../../)
* Библиотека [Aspose.Slides](../../../)