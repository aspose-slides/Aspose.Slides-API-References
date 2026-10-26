---
title: StartsWith()
second_title: Aspose.Slides لـ C++ مرجع API
description: يتحقق مما إذا كانت السلسلة تبدأ بالجزء المحدد.
type: docs
weight: 469
url: /ar/system/string/startswith/
---
## String::StartsWith(const String\&) const طريقة

يتحقق مما إذا كانت السلسلة تبدأ بالجزء الفرعي المحدد.

```cpp
bool System::String::StartsWith(const String &value) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../)\& | سلسلة البحث. |

### قيمة الإرجاع

true إذا بدأت السلسلة بالجزء الفرعي المحدد، false وإلا.

## String::StartsWith(const String\&, System::StringComparison) const طريقة

يتحقق مما إذا كانت السلسلة تبدأ بالجزء الفرعي المحدد.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../)\& | سلسلة البحث. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) الوضع، انظر [System::StringComparison](../../stringcomparison/) للتفاصيل. |

### قيمة الإرجاع

true إذا بدأت السلسلة بالجزء الفرعي المحدد، false وإلا.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const طريقة

يتحقق مما إذا كانت السلسلة تبدأ بالجزء الفرعي المحدد.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../)\& | سلسلة البحث. |
| ignoreCase | **bool** | يحدد ما إذا كان المقارنة غير حساسة لحالة الأحرف. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | الثقافة المستخدمة أثناء إجراء مقارنة السلسلة. |

### قيمة الإرجاع

true إذا بدأت السلسلة بالجزء الفرعي المحدد، false وإلا.

## انظر أيضًا

* تعداد [StringComparison](../../stringcomparison/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)