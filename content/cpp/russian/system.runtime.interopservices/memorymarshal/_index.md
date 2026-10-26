---
title: MemoryMarshal
second_title: Aspose.Slides для C++: справочник API
description: Предоставляет реализацию маршаллинга памяти. Только для совместимости с транслированным кодом, поскольку управляемый код не поддерживается на стороне C++. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры любыми способами.
type: docs
weight: 27
url: /ru/system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal класс


Предоставляет реализацию маршаллинга памяти. Только для совместимости с транслированным кодом, так как управляемый код не поддерживается на стороне C++. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры любыми способами.

```cpp
class MemoryMarshal
```

## Методы

| Метод | Описание |
| --- | --- |
| static [Span](../../system/span/)\<**uint8_t**\> [AsBytes](./asbytes/)(const [Span](../../system/span/)\<T\>\&) | Преобразует [Span](../../system/span/) одного примитивного типа T в [Span](../../system/span/) байтов. |
| static [Span](../../system/span/)\<TTo\> [Cast](./cast/)(const [Span](../../system/span/)\<TFrom\>\&) | Преобразует [Span](../../system/span/) одного примитивного типа TFrom в другой примитивный тип TTo. |
## См. также

* Простойство имён [System::Runtime::InteropServices](../)
* Библиотека [Aspose.Slides](../../)