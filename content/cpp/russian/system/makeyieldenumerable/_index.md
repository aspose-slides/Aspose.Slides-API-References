---
title: MakeYieldEnumerable()
second_title: Справочник API Aspose.Slides для C++
description: Создает IEnumerable из функции-генератора.
type: docs
weight: 2380
url: /ru/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) функция


Создает IEnumerable из функции-генератора.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в последовательности |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | Функция-генератор для выполнения |

### Возвращаемое значение

Указатель shared pointer на IEnumerable

## См. также

* Определение типа [SharedPtr](../sharedptr/)
* Класс [IEnumerable](../../system.collections.generic/ienumerable/)
* Пространство имен [System](../)
* Библиотека [Aspose.Slides](../../)