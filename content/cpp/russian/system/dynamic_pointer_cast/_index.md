---
title: dynamic_pointer_cast()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует умные указатели с помощью dynamic_cast.
type: docs
weight: 2887
url: /ru/system/dynamic_pointer_cast/
---
## System::dynamic_pointer_cast(SmartPtr\<X\> const\&) функция

Преобразует умные указатели с помощью dynamic_cast.

```cpp
template<class Y,class X> SmartPtr<Y> System::dynamic_pointer_cast(SmartPtr<X> const &x)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| X | Тип объекта, на который указывает указатель-источник. |
| Y | Тип объекта, на который указывает указатель-назначения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Указатель-источник. |

### Возвращаемое значение

Указатель после приведения.

## См. также

* Класс [SmartPtr](../smartptr/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)