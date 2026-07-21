---
title: GetDescription()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает имя константы перечисления, имеющей указанное значение.
type: docs
weight: 53
url: /ru/system/enum/getdescription/
---
## Enum::GetDescription(T) метод

Возвращает имя константы перечисления, имеющей указанное значение.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | T | Значение константы перечисления, имя которой нужно вернуть |

### Возвращаемое значение

Имя указанной константы перечисления

## См. также

* Тип [UnderlyingType](../underlyingtype/)
* Класс [String](../../string/)
* Структура [Enum](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)