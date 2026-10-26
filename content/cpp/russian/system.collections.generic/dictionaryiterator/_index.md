---
title: DictionaryIterator
second_title: Справочник API Aspose.Slides для C++
description: Итератор словаря, предоставляющий нотацию KeyValuePair.
type: docs
weight: 157
url: /ru/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator класс


[Dictionary](../dictionary/) итератор, который предоставляет [KeyValuePair](../keyvaluepair/) нотацию.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Dict | [Dictionary](../dictionary/) класс. |
## Методы

| Метод | Описание |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | Клонирует текущий итератор. |
| void [DecrementIterator](./decrementiterator/)() override | Перемещает итератор на один шаг назад. |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Конструктор. |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Конструктор. |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | Конструктор перемещения. |
| void [IncrementIterator](./incrementiterator/)() override | Перемещает итератор на один шаг вперёд. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Перемещает итератор на указанное количество шагов. |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | Деструктор. |

## См. также

* Пространство имён [System::Collections::Generic](../)
* Библиотека [Aspose.Slides](../../)