---
title: EndsWith()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يتحقق مما إذا كانت السلسلة تنتهي بالجزء المحدد.
type: docs
weight: 482
url: /ar/system/string/endswith/
---
## String::EndsWith(const String\&) const طريقة

يتحقق مما إذا كانت السلسلة تنتهي بالجزء المحدد.

```cpp
bool System::String::EndsWith(const String &value) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../)\& | سلسلة البحث. |

### قيمة الإرجاع

true إذا انتهت السلسلة بالجزء المحدد، false خلاف ذلك.

## String::EndsWith(const String\&, System::StringComparison) const طريقة

يتحقق مما إذا كانت السلسلة تنتهي بالجزء المحدد.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../)\& | سلسلة البحث. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) وضع، راجع [System::StringComparison](../../stringcomparison/) للتفاصيل. |

### قيمة الإرجاع

true إذا انتهت السلسلة بالجزء المحدد، false خلاف ذلك.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const طريقة

يتحقق مما إذا كانت السلسلة تنتهي بالجزء المحدد.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../)\& | سلسلة البحث. |
| ignoreCase | **bool** | يحدد ما إذا كانت المقارنة غير حساسة لحالة الأحرف. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | الثقافة المستخدمة أثناء إجراء مقارنة السلسلة. |

### قيمة الإرجاع

true إذا انتهت السلسلة بالجزء المحدد، false خلاف ذلك.

## انظر أيضًا

* تعداد [StringComparison](../../stringcomparison/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* مساحة أسماء [System](../../)
* مكتبة [Aspose.Slides](../../../)