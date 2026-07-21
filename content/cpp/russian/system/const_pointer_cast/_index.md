---
title: const_pointer_cast()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует умные указатели с помощью const_cast.
type: docs
weight: 2900
url: /ru/system/const_pointer_cast/
---
## System::const_pointer_cast(SmartPtr\<X\> const\&) функция

Преобразует умные указатели с помощью const_cast.

```cpp
template<class Y,class X> SmartPtr<Y> System::const_pointer_cast(SmartPtr<X> const &x)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| X | Тип объекта, на который указывает исходный указатель. |
| Y | Тип объекта, на который указывает целевой указатель. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Исходный указатель. |

### Возвращаемое значение

Указатель после приведения.

## См. также

* Класс [SmartPtr](../smartptr/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)