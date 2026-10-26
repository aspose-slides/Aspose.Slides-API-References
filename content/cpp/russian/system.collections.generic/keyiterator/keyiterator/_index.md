---
title: KeyIterator()
second_title: Справочник API Aspose.Slides для C++
description: Конструктор.
type: docs
weight: 1
url: /ru/system.collections.generic/keyiterator/keyiterator/
---
## KeyIterator::KeyIterator(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) конструктор

Конструктор.

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(typename Dict::map_t::const_iterator &&iterator, typename Dict::map_t::const_iterator &&end) noexcept
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| iterator | typename Dict::map_t::const_iterator\&& | Итератор для хранения. |
| end | typename Dict::map_t::const_iterator\&& | Итератор до конца контейнера. |

## KeyIterator::KeyIterator(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) конструктор

Конструктор.

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(const typename Dict::map_t::const_iterator &iterator, const typename Dict::map_t::const_iterator &end)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| iterator | const typename Dict::map_t::const_iterator\& | Итератор для хранения. |
| end | const typename Dict::map_t::const_iterator\& | Итератор до конца контейнера. |

## KeyIterator::KeyIterator(KeyIterator\&&) конструктор

Конструктор перемещения.

```cpp
System::Collections::Generic::KeyIterator<Dict>::KeyIterator(KeyIterator &&other) noexcept
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [KeyIterator](../)\&& | Итератор, из которого перемещаются данные. |

## См. также

* Класс [KeyIterator](../)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)