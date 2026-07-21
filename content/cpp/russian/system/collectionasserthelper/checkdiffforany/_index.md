---
title: CheckDiffForAny()
second_title: Aspose.Slides для C++ API Reference
description: Проверяет, что любой элемент коллекции соответствует предикату.
type: docs
weight: 27
url: /ru/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) метод

Проверяет, что любой элемент коллекции удовлетворяет предикату.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Предикат для проверки. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Значения для проверки. |

### Возвращаемое значение

true если проверка проходит для любого элемента, false если проверка не проходит ни для одного.

## См. также

* typedef [SharedPtr](../../sharedptr/)
* Класс [ICollection](../../../system.collections.generic/icollection/)
* Структура [CollectionAssertHelper](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)