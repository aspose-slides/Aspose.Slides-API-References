---
title: what()
second_title: Справочник API Aspose.Slides для C++
description: "Реализует метод what(), который вызывается классом ExceptionWrapper. Несмотря на то, что этот класс не наследуется от std::exception, производные классы могут использовать protected/private члены для реализации своей логики. Перемещение реализации этого метода в ExceptionWrapper может нарушить эту логику."
type: docs
weight: 105
url: /ru/system/details_exception/what/
---
## Details_Exception::what() const method

Implements [what()](./) method which is called by [ExceptionWrapper](../../exceptionwrapper/) класс. Несмотря на то, что этот класс не наследуется от std::exception, производные классы могут использовать protected/private члены для реализации своей логики. Перемещение реализации этого метода в [ExceptionWrapper](../../exceptionwrapper/) может нарушить эту логику.

```cpp
virtual const char * System::Details_Exception::what() const noexcept
```

### Возвращаемое значение

Описание исключения.

## См. также

* Класс [Details_Exception](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)