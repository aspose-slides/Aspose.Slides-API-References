---
title: operator==()
second_title: Aspose.Slides для C++ справочник API
description: Сравнивает две пары ключ-значение, используя семантику 'equals'. Использует оператор == или метод EqualsTo для обоих ключей и значений, в зависимости от того, какой определён.
type: docs
weight: 690
url: /ru/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) function


Сравнивает две пары ключ-значение, используя семантику 'equals'. Использует оператор == или метод EqualsTo для обоих ключей и значений, в зависимости от того, какой определён.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| TKey | Тип ключа. |
| TValue | Тип значения. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Операнд слева. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Операнд справа. |

### Возвращаемое значение

True если обе ключа и значения совпадают, false в противном случае.

## См. также

* Class [KeyValuePair](../keyvaluepair/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)