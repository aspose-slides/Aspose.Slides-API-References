---
title: SetSynchronizationContext()
second_title: Aspose.Slides for C++ справка по API
description: Устанавливает контекст синхронизации для текущего потока.
type: docs
weight: 53
url: /ru/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) метод


Устанавливает контекст синхронизации для текущего потока.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | Контекст синхронизации, который нужно установить для текущего потока. |
## Примечания



Передача nullptr очистит контекст синхронизации для текущего потока. 

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [SynchronizationContext](../)
* Пространство имён [System::Threading](../../)
* Библиотека [Aspose.Slides](../../../)