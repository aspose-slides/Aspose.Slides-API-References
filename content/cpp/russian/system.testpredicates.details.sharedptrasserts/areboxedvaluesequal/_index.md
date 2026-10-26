---
title: AreBoxedValuesEqual()
second_title: Aspose.Slides для C++ – справочник API
description: Сравнивает два типа Boxed на равенство.
type: docs
weight: 79
url: /ru/system.testpredicates.details.sharedptrasserts/areboxedvaluesequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreBoxedValuesEqual(const char *, const char *, const SharedPtr\<BoxedValueBase\>\&, const SharedPtr\<BoxedValueBase\>\&) функция


Сравнивает два типа Boxed на равенство.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreBoxedValuesEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<BoxedValueBase> &lhs, const SharedPtr<BoxedValueBase> &rhs)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[BoxedValueBase](../../system/boxedvaluebase/)\>\& | Значение LHS. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[BoxedValueBase](../../system/boxedvaluebase/)\>\& | Значение RHS. |

### Возвращаемое значение

результат утверждения в стиле gtest.

## См. также

* typedef [SharedPtr](../../system/sharedptr/)
* class [BoxedValueBase](../../system/boxedvaluebase/)
* namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* library [Aspose.Slides](../../)