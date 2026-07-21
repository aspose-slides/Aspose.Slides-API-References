---
title: CollectionsToMsg()
second_title: Aspose.Slides для справки API на C++
description: Сериализует две коллекции для представления сообщения.
type: docs
weight: 53
url: /ru/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String&, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>>&, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>>&) метод


Сериализует две коллекции для представления сообщения.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T1 | Expected collection element type. |
| T2 | Actual collection element type. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)& | A custom string which is inserted before the expected value in the resulting message |
| expected | const [System::SharedPtr](../../sharedptr/)<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)<T1>>& | Expected collection. |
| actual | const [System::SharedPtr](../../sharedptr/)<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)<T2>>& | Actual collection. |

### Возвращаемое значение

Понятное сообщение о содержимом коллекций.

## См. также

* typedef [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [IEnumerable](../../../system.collections.generic/ienumerable/)
* Структура [CollectionAssertHelper](../)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)