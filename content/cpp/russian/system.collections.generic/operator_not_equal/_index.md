---
title: operator!=()
second_title: Справочный документ API Aspose.Slides для C++
description: Сравнивает две пары «ключ-значение», используя обратную семантику «равенства».
type: docs
weight: 703
url: /ru/system.collections.generic/operator_not_equal/
---
## System::Collections::Generic::operator!=(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) функция

Сравнивает две пары «ключ-значение», используя обратную семантику «равенства».

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator!=(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TKey | Тип ключа. |
| TValue | Тип значения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Операнд слева. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Операнд справа. |

### Возвращаемое значение

True если оба ключа и значения не совпадают, false в противном случае.

## См. также

* Класс [KeyValuePair](../keyvaluepair/)
* Пространство имён [System::Collections::Generic](../)
* Библиотека [Aspose.Slides](../../)