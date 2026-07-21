---
title: GetName()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает имя константы перечисления, имеющей указанное значение.
type: docs
weight: 40
url: /ru/system/enum/getname/
---
## Enum::GetName(T) метод

Возвращает имя константы перечисления, имеющей указанное значение.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | T | Значение константы перечисления, имя которой должно быть возвращено |

### Возвращаемое значение

Имя указанной константы перечисления

## См. также

* Типовое определение [UnderlyingType](../underlyingtype/)
* Класс [String](../../string/)
* Структура [Enum](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)