---
title: KeyIterator
second_title: Справка API Aspose.Slides для C++
description: Итератор словаря, предоставляющий доступ к ключам.
type: docs
weight: 365
url: /ru/system.collections.generic/keyiterator/
---
## KeyIterator класс

[Dictionary](../dictionary/) итератор, предоставляющий доступ к ключам.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Dict | [Dictionary](../dictionary/) класс. |

## Методы

| Метод | Описание |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | Клонирует текущий итератор. |
| void [DecrementIterator](./decrementiterator/)() override | Перемещает итератор на один шаг назад. |
| void [IncrementIterator](./incrementiterator/)() override | Перемещает итератор на один шаг вперёд. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Конструктор. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Конструктор. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | Конструктор перемещения. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Перемещает итератор на указанное количество шагов. |
| virtual  [~KeyIterator](./~keyiterator/)() | Деструктор. |

## См. также

* Пространство имён [System::Collections::Generic](../)
* Библиотека [Aspose.Slides](../../)