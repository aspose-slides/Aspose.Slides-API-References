---
title: MakeYieldEnumerator()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт IEnumerator из функции yield.
type: docs
weight: 2393
url: /ru/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) function

Создаёт IEnumerator из функции yield.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | The type of elements in the sequence |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | The yield function to execute |

### Возвращаемое значение

Умный указатель на IEnumerator

## См. также

* Тип-определение [SharedPtr](../sharedptr/)
* Класс [IEnumerator](../../system.collections.generic/ienumerator/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)