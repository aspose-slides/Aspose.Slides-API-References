---
title: Cast_noexcept()
second_title: Справочник API Aspose.Slides для C++
description: Выполняет приведение типов объектов SmartPtr.
type: docs
weight: 2458
url: /ru/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) функция


Выполняет приведение типов для объектов [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TTo | Тип целевого указателя. |
| TFrom | Тип исходного указателя. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Указатель на источник. |

### Возвращаемое значение

Результат приведения, если приведение разрешено, иначе nullptr.

## См. также

* Класс [SmartPtr](../smartptr/)
* Структура [IsExceptionWrapper](../isexceptionwrapper/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)