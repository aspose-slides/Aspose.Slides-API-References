---
title: ValueIterator
second_title: Aspose.Slides для C++ API Reference
description: Итератор словаря, предоставляющий доступ к значениям.
type: docs
weight: 625
url: /ru/system.collections.generic/valueiterator/
---
## ValueIterator класс

[Dictionary](../dictionary/) итератор, предоставляющий доступ к значениям.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Dict | [Dictionary](../dictionary/) класс. |

## Методы

| Метод | Описание |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | Создаёт копию текущего итератора. |
| void [DecrementIterator](./decrementiterator/)() override | Перемещает итератор на шаг назад. |
| void [IncrementIterator](./incrementiterator/)() override | Перемещает итератор на шаг вперёд. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Перемещает итератор на указанное количество шагов. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Конструктор. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Конструктор. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | Конструктор перемещения. |
| virtual  [~ValueIterator](./~valueiterator/)() | Деструктор. |

## См. также

* Пространство имён [System::Collections::Generic](../)
* Библиотека [Aspose.Slides](../../)