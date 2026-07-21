---
title: get_Current()
second_title: Справочник API Aspose.Slides для C++
description: Получает контекст синхронизации для текущего потока.
type: docs
weight: 40
url: /ru/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current() метод


Получает контекст синхронизации для текущего потока.

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```


### Возвращаемое значение

SharedPtr<SynchronizationContext> Общий указатель на контекст синхронизации текущего потока.
## Примечания



Возвращает null, если для текущего потока не установлен контекст синхронизации. 

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [SynchronizationContext](../)
* Пространство имён [System::Threading](../../)
* Библиотека [Aspose.Slides](../../../)