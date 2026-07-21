---
title: Yield()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт ожидаемую задачу, которая асинхронно возвращает управление текущему контексту при ожидании.
type: docs
weight: 222
url: /ru/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() функция

Создаёт ожидаемую задачу, которая асинхронно возвращает управление текущему контексту при ожидании.

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```

### Возвращаемое значение

YieldAwaitable, который можно ожидать, чтобы передать управление.

## Замечания

Этот метод полезен для принудительного передачи управления асинхронным методом, позволяя обработать другие ожидающие задачи перед продолжением.

## См. также

* Класс [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* Пространство имён [System::Threading::Tasks](../)
* Библиотека [Aspose.Slides](../../)