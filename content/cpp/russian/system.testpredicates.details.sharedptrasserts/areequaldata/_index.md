---
title: AreEqualData()
second_title: Aspose.Slides для C++ справочник API
description: "Сравнивает два контейнера на равенство, используя System::Object::Equals по элементам. Работает с элементами SmartPtr."
type: docs
weight: 14
url: /ru/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) функция

Сравнивает два контейнера на равенство, используя [System::Object::Equals](../../system/object/equals/) по элементам. Работает с элементами [SmartPtr](../../system/smartptr/).

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип контейнера слева (LHS). |
| T2 | Тип контейнера справа (RHS). |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | const T1\& | Ссылка на контейнер слева (LHS). |
| rhs | const T2\& | Ссылка на контейнер справа (RHS). |

### Возвращаемое значение

true, если содержащиеся элементы и размеры совпадают, иначе false.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) функция

Сравнивает два контейнера на равенство, используя оператор == по элементам. Работает с элементами, не являющимися SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип контейнера слева (LHS). |
| T2 | Тип контейнера справа (RHS). |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | const T1\& | Контейнер слева (LHS). |
| rhs | const T2\& | Контейнер справа (RHS). |

### Возвращаемое значение

true, если содержащиеся элементы и размеры совпадают, иначе false.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T\&, const T\&) функция

Сравнивает два контейнера одинакового типа на равенство. Работает с элементами, не являющимися SmartPtr.

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип контейнера слева (LHS). |
| T2 | Тип контейнера справа (RHS). |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | const T\& | Контейнер слева (LHS). |
| rhs | const T\& | Контейнер справа (RHS). |

### Возвращаемое значение

true, если содержащиеся элементы и размеры совпадают, иначе false.

## См. также

* Структура [IsSmartPtr](../../system/issmartptr/)
* Пространство имён [System::TestPredicates::Details::SharedPtrAsserts](../)
* Библиотека [Aspose.Slides](../../)