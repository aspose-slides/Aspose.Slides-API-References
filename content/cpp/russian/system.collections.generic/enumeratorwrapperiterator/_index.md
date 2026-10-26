---
title: EnumeratorWrapperIterator
second_title: Aspose.Slides для C++ справочник API
description: Итератор, который оборачивает предварительно созданный перечислитель и перенаправляет все вызовы к нему.
type: docs
weight: 196
url: /ru/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator класс


Итератор, который оборачивает предварительно созданный перечислитель и перенаправляет все вызовы к нему.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Element | Тип элемента. |
## Методы

| Метод | Описание |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | Создаёт копию текущего итератора. |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | Перемещает итератор на один шаг вперёд. Должен обновлять m_is_end и m_pointer. |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | Проверяет, указывают ли два итератора на один и тот же элемент. |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Деструктор. |

## Смотрите также

* Пространство имён [System::Collections::Generic](../)
* Библиотека [Aspose.Slides](../../)