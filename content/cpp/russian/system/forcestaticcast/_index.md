---
title: ForceStaticCast()
second_title: Aspose.Slides для C++ справочник API
description: Выполняет реальное статическое приведение типов объектов SmartPtr.
type: docs
weight: 2549
url: /ru/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const&) функция


Выполняет реальное статическое приведение типов для объектов [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TTo | Тип указателя назначения. |
| TFrom | Тип указателя источника. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Указатель-источник. |

### Возвращаемое значение

Результат приведения, если приведение разрешено; в противном случае поведение не определено.

## См. также

* Класс [SmartPtr](../smartptr/)
* Структура [CastResult](../castresult/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)