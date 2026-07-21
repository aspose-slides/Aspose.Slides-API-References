---
title: Cast()
second_title: Aspose.Slides для C++ - справка API
description: Выполняет приведение типов для объектов SmartPtr.
type: docs
weight: 2471
url: /ru/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) функция

Выполняет приведение типов для объектов [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TTo | Тип целевого указателя. |
| TFrom | Тип исходного указателя. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Исходный указатель. |

### Возвращаемое значение

Результат приведения, если приведение разрешено.

## См. также

* Класс [SmartPtr](../smartptr/)
* Структура [IsExceptionWrapper](../isexceptionwrapper/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)