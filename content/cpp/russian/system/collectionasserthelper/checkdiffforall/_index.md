---
title: CheckDiffForAll()
second_title: Aspose.Slides для C++ справочник API
description: Проверяет, что все элементы коллекции соответствуют предикату.
type: docs
weight: 14
url: /ru/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) method


Проверяет, что все элементы коллекции соответствуют предикату.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Предикат для проверки. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Значения для проверки. |

### Возвращаемое значение

False, если проверка не проходит для любого элемента, true, если все проходят.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)