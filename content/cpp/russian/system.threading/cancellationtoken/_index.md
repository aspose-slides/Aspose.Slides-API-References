---
title: CancellationToken
second_title: Справочник API Aspose.Slides для C++
description: Распространяет уведомление о том, что операции следует отменить. Этот класс предоставляет механизм кооперативной отмены между потоками, позволяя одному потоку уведомлять другие, что операцию следует отменить.
type: docs
weight: 14
url: /ru/system.threading/cancellationtoken/
---
## CancellationToken класс


Propagates notification that operations should be canceled. This class provides a mechanism for cooperative cancellation between threads, allowing one thread to notify others that an operation should be canceled.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## Методы

| Метод | Описание |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | Конструктор по умолчанию. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | Возвращает, может ли этот токен находиться в состоянии отмены. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Возвращает, был ли запрошен запрос на отмену для этого токена. |
| static [CancellationToken](./) [get_None](./get_none/)() | Возвращает пустое значение [System::Threading::CancellationToken](./). |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | Регистрирует обратный вызов, который будет выполнен, когда будет запрошена отмена. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | Выбрасывает OperationCanceledException, если отмена была запрошена. |
## Примечания



Экземпляр [CancellationToken](./) может быть отменён только через его связанный [CancellationTokenSource](../cancellationtokensource/). 

## См. также

* Namespace [System::Threading](../)
* Library [Aspose.Slides](../../)