---
title: NotNullAreNotEqualImpl()
second_title: Aspose.Slides для C++ - справочник API
description: Сравнивает массивы или списки на неравенство.
type: docs
weight: 105
url: /ru/system.testpredicates.details.sharedptrasserts/notnullarenotequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) функция

Сравнивает массивы или списки на неравенство.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип контейнера LHS. |
| T2 | Тип контейнера RHS. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const T1\& | Значение LHS. |
| rhs | const T2\& | Значение RHS. |
| s | long long | Служебный параметр, используемый как селектор реализации функции; значение параметра игнорируется |

### Возвращаемое значение

Результат утверждения в стиле gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) функция

Сравнивает экземпляры IEnumerable на неравенство.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип элемента LHS. |
| T2 | Тип элемента RHS. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const T1\& | Значение LHS. |
| rhs | const T2\& | Значение RHS. |
| s | long long | Служебный параметр, используемый как селектор реализации функции; значение параметра игнорируется |

### Возвращаемое значение

Результат утверждения в стиле gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) функция

Сравнивает неизвестные типы на неравенство, используя метод Eqauals.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип объекта LHS. |
| T2 | Тип объекта RHS. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const T1\& | Значение LHS. |
| rhs | const T2\& | Значение RHS. |

### Возвращаемое значение

Результат утверждения в стиле gtest.

## См. также

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struct [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)