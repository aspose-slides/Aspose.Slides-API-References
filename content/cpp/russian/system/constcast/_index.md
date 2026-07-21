---
title: ConstCast()
second_title: Справочник API Aspose.Slides для C++
description: Конец устаревших приведений.
type: docs
weight: 2536
url: /ru/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) функция

Конец устаревших приведений.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TTo | Тип целевого указателя. |
| TFrom | Тип исходного указателя. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | Указатель источника. |

### Возвращаемое значение

Результат приведения, если приведение разрешено, иначе nullptr.

## Замечания

Выполняет const-cast над объектами [SmartPtr](../smartptr/).

## См. также

* Класс [SmartPtr](../smartptr/)
* Структура [CastResult](../castresult/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)