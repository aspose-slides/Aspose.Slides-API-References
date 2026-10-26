---
title: DoTryFinally()
second_title: مرجع API الخاص بـ Aspose.Slides للـ C++
description: الدالة الوحيدة التي تحاكي سلوك عبارة try[-catch]-finally في C#. أثناء ترجمة عبارة try[-catch]-finally في C# باستخدام خيار المترجم finally_statement_as_lambda المعين إلى true، يتم ترجمة العبارة إلى استدعاء هذه الطريقة.
type: docs
weight: 2445
url: /ar/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) دالة

الدالة الوحيدة التي تحاكي سلوك عبارة try[-catch]-finally في C#. أثناء ترجمة عبارة try[-catch]-finally في C# باستخدام خيار المترجم finally_statement_as_lambda المعين إلى true، يتم ترجمة العبارة إلى استدعاء هذه الطريقة.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع كائن الدالة الذي ينفذ جزء try[-catch] من عبارة try[-catch]-finally التي يتم محاكاتها |
| F | نوع كائن الدالة الذي ينفذ جزء finally من عبارة try[-catch]-finally التي يتم محاكاتها |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| tryBlock | T\&& | كائن الدالة الذي يحتوي جسمه تطبيق جزء try[-catch] من عبارة try[-catch]-finally التي يتم محاكاتها |
| finallyBlock | F\&& | كائن الدالة الذي يحتوي جسمه تطبيق جزء finally من عبارة try[-catch]-finally التي يتم محاكاتها |

## System::DoTryFinally(T\&&, F\&&) دالة

الدالة الوحيدة التي تحاكي سلوك عبارة try[-catch]-finally في C#. أثناء ترجمة عبارة try[-catch]-finally في C# باستخدام خيار المترجم finally_statement_as_lambda المعين إلى true، يتم ترجمة العبارة إلى استدعاء هذه الطريقة. هذا التحميل الزائد يتعامل مع الحالة التي تكون فيها القيمة المرجعة لكائن الدالة الذي ينفذ جزء try[-catch] من عبارة try[-catch]-finally من نوع bool.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع كائن الدالة الذي ينفذ جزء try[-catch] من عبارة try[-catch]-finally التي يتم محاكاتها |
| F | نوع كائن الدالة الذي ينفذ جزء finally من عبارة try[-catch]-finally التي يتم محاكاتها |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| tryBlock | T\&& | كائن الدالة الذي يحتوي جسمه تطبيق جزء try[-catch] من عبارة try[-catch]-finally التي يتم محاكاتها |
| finallyBlock | F\&& | كائن الدالة الذي يحتوي جسمه تطبيق جزء finally من عبارة try[-catch]-finally التي يتم محاكاتها |

## System::DoTryFinally(T\&&, F\&&) دالة

الدالة الوحيدة التي تحاكي سلوك عبارة try[-catch]-finally في C#. أثناء ترجمة عبارة try[-catch]-finally في C# باستخدام خيار المترجم finally_statement_as_lambda المعين إلى true، يتم ترجمة العبارة إلى استدعاء هذه الطريقة. هذا التحميل الزائد يتعامل مع الحالة التي تكون فيها القيمة المرجعة لكائن الدالة الذي ينفذ جزء try[-catch] من عبارة try[-catch]-finally من نوع bool&.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع كائن الدالة الذي ينفذ جزء try[-catch] من عبارة try[-catch]-finally التي يتم محاكاتها |
| F | نوع كائن الدالة الذي ينفذ جزء finally من عبارة try[-catch]-finally التي يتم محاكاتها |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| tryBlock | T\&& | كائن الدالة الذي يحتوي جسمه تطبيق جزء try[-catch] من عبارة try[-catch]-finally التي يتم محاكاتها |
| finallyBlock | F\&& | كائن الدالة الذي يحتوي جسمه تطبيق جزء finally من عبارة try[-catch]-finally التي يتم محاكاتها |

## راجع أيضًا

* المجال [System](../)
* المكتبة [Aspose.Slides](../../)