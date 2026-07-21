---
title: KeyValuePair()
second_title: Aspose.Slides для C++ API Reference
description: Инициализатор пустой пары ключ-значение.
type: docs
weight: 1
url: /ru/system.collections.generic/keyvaluepair/keyvaluepair/
---
## KeyValuePair::KeyValuePair() конструктор

Инициализатор пустой пары ключ-значение.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair()
```

## KeyValuePair::KeyValuePair(const TKey&, const TValue&) конструктор

Конструктор.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const TKey &key, const TValue &value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | const TKey& | Ключ. |
| value | const TValue& | Значение. |

## KeyValuePair::KeyValuePair(const std::pair\<OtherK, OtherV\>&) конструктор

Конструктор преобразования типа.

```cpp
template<typename OtherK,typename OtherV> System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const std::pair<OtherK, OtherV> &pair)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| OtherK | Тип другого ключа. |
| OtherV | Тип другого значения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pair | const std::pair\<OtherK, OtherV\>& | Значение пары. |

## См. также

* Класс [KeyValuePair](../)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)