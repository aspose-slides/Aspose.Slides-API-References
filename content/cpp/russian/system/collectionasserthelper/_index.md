---
title: CollectionAssertHelper
second_title: Aspose.Slides для справочника по API C++
description: API помощника для операций, связанных с коллекциями.
type: docs
weight: 1522
url: /ru/system/collectionasserthelper/
---
## CollectionAssertHelper структура

API помощника для операций, связанных с коллекциями.

```cpp
class CollectionAssertHelper
```

## Методы

| Метод | Описание |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Проверяет, что все элементы коллекции соответствуют предикату. |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Проверяет, что любой элемент коллекции соответствует предикату. |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Сериализует две коллекции для представления сообщения. |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | Преобразует коллекцию в строку, объединяя строковые представления элементов. |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Вычисляет «разницу» между двумя коллекциями. Для каждого элемента каждой коллекции в качестве ключа получаемое значение будет положительным, если элемент встречается больше раз в коллекции \"expected\", отрицательным, если элемент встречается больше раз в коллекции \"actual\", и нулевым, если элемент встречается одинаковое количество раз в обеих коллекциях. |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | Форматирует строку для использования в качестве текста сообщения. |

## Смотрите также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)