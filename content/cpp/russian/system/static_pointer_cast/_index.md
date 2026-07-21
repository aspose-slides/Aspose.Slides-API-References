---
title: static_pointer_cast()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует умные указатели с помощью static_cast.
type: docs
weight: 2874
url: /ru/system/static_pointer_cast/
---
## System::static_pointer_cast(SmartPtr\<X\> const\&) функция

Преобразует умные указатели с использованием static_cast.

```cpp
template<class Y,class X> SmartPtr<Y> System::static_pointer_cast(SmartPtr<X> const &x)
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| X | Тип объекта, на который указывает исходный указатель. |
| Y | Тип объекта, на который указывает целевой указатель. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Исходный указатель. |

### Возвращаемое значение

Указатель после приведения.

## См. также

* Класс [SmartPtr](../smartptr/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)