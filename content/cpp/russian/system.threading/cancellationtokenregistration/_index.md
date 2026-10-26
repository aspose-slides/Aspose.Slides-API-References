---
title: CancellationTokenRegistration
second_title: Aspose.Slides for C++ Справочник API
description: Представляет регистрацию обратного вызова токена отмены.
type: docs
weight: 27
url: /ru/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration класс


Представляет регистрацию для обратного вызова токена отмены.

```cpp
class CancellationTokenRegistration
```

## Методы

| Метод | Описание |
| --- | --- |
| void [Dispose](./dispose/)() | Освобождает регистрацию и удаляет обратный вызов из связанного [CancellationTokenSource](../cancellationtokensource/). После вызова этого метода зарегистрированный обратный вызов больше не будет вызываться, когда связанный [CancellationTokenSource](../cancellationtokensource/) будет отменён. |
## Замечания


Этот класс позволяет отменить регистрацию обратного вызова из токена отмены. При освобождении он удаляет обратный вызов из связанного [CancellationTokenSource](../cancellationtokensource/). 
Этот класс не должен создаваться напрямую — он возвращается методами регистрации [CancellationToken](../cancellationtoken/). 

## См. также

* Пр пространство имён [System::Threading](../)
* Библиотека [Aspose.Slides](../../)