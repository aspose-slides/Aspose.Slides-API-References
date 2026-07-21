---
title: Register()
second_title: Справка API Aspose.Slides для C++
description: Регистрирует обратный вызов, который будет выполнен, когда запрошена отмена.
type: docs
weight: 40
url: /ru/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const method


Регистрирует обратный вызов, который будет выполнен, когда запрошена отмена.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | Action<>, который будет выполнен, когда запрошена отмена. |

### Возвращаемое значение

Объект [CancellationTokenRegistration](../../cancellationtokenregistration/), который можно использовать для отмены регистрации обратного вызова.

## Примечания

Если отмена уже была запрошена, обратный вызов будет выполнен немедленно. 

Обратный вызов должен быть короткоживущим и не блокирующим, так как он будет выполнен в потоке, вызывающем Cancel() у [CancellationTokenSource](../../cancellationtokensource/). 

## См. также

* Типовое определение [Action](../../../system/action/)
* Класс [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Класс [CancellationToken](../)
* Пространство имён [System::Threading](../../)
* Библиотека [Aspose.Slides](../../../)