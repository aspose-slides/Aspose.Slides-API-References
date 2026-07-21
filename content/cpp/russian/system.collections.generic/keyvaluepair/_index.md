---
title: KeyValuePair
second_title: Справочник API Aspose.Slides для C++
description: "Пара ключа и значения. Этот тип должен быть размещён в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа."
type: docs
weight: 378
url: /ru/system.collections.generic/keyvaluepair/
---
## KeyValuePair класс

Пара ключа и значения. Этот тип должен быть размещён в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте [System::SmartPtr](../../system/smartptr/) класс для управления объектами этого типа.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Методы

| Метод | Описание |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | Получает ключ. |
| const TValue\& [get_Value](./get_value/)() const | Получает значение. |
| int [GetHashCode](./gethashcode/)() const | Вычисляет хеш пары ключ-значение, используя XOR хешей ключа и значения. |
| **bool** [IsNull](./isnull/)() const | Всегда возвращает false. |
|  [KeyValuePair](./keyvaluepair/)() | Инициализатор пустой пары ключ-значение. |
|  [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Конструктор. |
|  [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Конструктор преобразования типа. |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | Заплатка для классов, наследуемых от IComparer<KeyValuePair<TKey, TValue>>, не сравнивает ничего. |
| [String](../../system/string/) [ToString](./tostring/)() const | Преобразует пару ключ-значение в строку. |

## См. также

* Пространство имён [System::Collections::Generic](../)
* Библиотека [Aspose.Slides](../../)