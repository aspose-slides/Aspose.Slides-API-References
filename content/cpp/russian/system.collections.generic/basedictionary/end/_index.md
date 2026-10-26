---
title: end()
second_title: Aspose.Slides для C++ справки API
description: Возвращает итератор к обёртке KVPair для элемента key-value, следующего за последним элементом контейнера. Реализовано в стиле C# — итератор должен возвращать объект KVPair с интерфейсом get_Key() и get_Value(). Этот элемент служит заполняющим местом; попытка доступа к нему приводит к неопределённому поведению.
type: docs
weight: 235
url: /ru/system.collections.generic/basedictionary/end/
---
## BaseDictionary::end() const метод

Возвращает итератор к KVPair-wrapper для key-value-element, следующего за последним элементом контейнера. Реализовано в стиле C# — итератор должен возвращать KVPair-object с интерфейсом get_Key() и get_Value(). Этот элемент выступает в качестве заполняющего места; попытка доступа к нему приводит к неопределённому поведению.

```cpp
const_iterator System::Collections::Generic::BaseDictionary<Map>::end() const noexcept
```

### Возвращаемое значение

Итератор, указывающий на теоретический элемент, размещённый после конечного элемента коллекции.

## См. также

* typedef [const_iterator](../const_iterator/)
* Класс [BaseDictionary](../)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)