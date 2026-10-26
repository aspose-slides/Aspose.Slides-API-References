---
title: AreEqualContainer()
second_title: Справочник API Aspose.Slides для C++
description: Сравнивает два контейнера на равенство, используя оператор == для элементов. Работает с элементами, не являющимися SmartPtr.
type: docs
weight: 1
url: /ru/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) функция


Сравнивает два контейнера на равенство, используя оператор == для элементов. Работает с элементами, не являющимися SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип контейнера LHS. |
| T2 | Тип контейнера RHS. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | const T1\& | Контейнер LHS. |
| rhs | const T2\& | Контейнер RHS. |

### Возвращаемое значение

True if contained elements and sizes match, false otherwise.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) функция


Сравнивает два контейнера на равенство, используя [System::Object::Equals](../../system/object/equals/) для элементов. Работает с элементами [SmartPtr](../../system/smartptr/).

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип контейнера LHS. |
| T2 | Тип контейнера RHS. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | const T1\& | Ссылка на контейнер LHS. |
| rhs | const T2\& | Ссылка на контейнер RHS. |

### Возвращаемое значение

True if contained elements and sizes match, false otherwise.

## См. также

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)