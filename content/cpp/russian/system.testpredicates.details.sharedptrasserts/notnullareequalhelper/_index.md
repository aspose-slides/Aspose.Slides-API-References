---
title: NotNullAreEqualHelper()
second_title: Справочник API Aspose.Slides для C++
description: Сравнивает абстрактные коллекции на равенство.
type: docs
weight: 66
url: /ru/system.testpredicates.details.sharedptrasserts/notnullareequalhelper/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualHelper(const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) функция


Сравнивает на равенство абстрактные коллекции.

```cpp
template<typename T> bool System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualHelper(const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | Тип элемента. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | Значение LHS. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | Значение RHS. |

### Возвращаемое значение

gtest-styled assertion result.

## Смотрите также

* Typedef [SharedPtr](../../system/sharedptr/)
* Класс [ICollection](../../system.collections.generic/icollection/)
* Пространство имён [System::TestPredicates::Details::SharedPtrAsserts](../)
* Библиотека [Aspose.Slides](../../)