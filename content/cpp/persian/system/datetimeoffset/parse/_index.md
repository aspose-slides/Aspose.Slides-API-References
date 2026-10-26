---
title: Parse()
second_title: Aspose.Slides برای C++ مرجع API
description: رشتهٔ مشخص‌شده را به معادل DateTimeOffset تبدیل می‌کند.
type: docs
weight: 703
url: /fa/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) متد

رشتهٔ مشخص‌شده را به معادل [DateTimeOffset](../) تبدیل می‌کند.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) برای تبدیل. |

### مقدار بازگشت

[DateTimeOffset](../) که معادل **input** است.

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) متد

رشتهٔ مشخص‌شده را با استفاده از فراهم‌کنندهٔ قالب‌گذاری و سبک قالب‌بندی مشخص‌شده، به شیء [DateTimeOffset](../) تبدیل می‌کند.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) برای تبدیل. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | فراهم‌کنندهٔ قالب. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | سبک‌های قالب‌بندی تاریخ و زمان. |

### مقدار بازگشت

[DateTimeOffset](../) که معادل **input** است.

## موارد مرتبط

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* کلاس [DateTimeOffset](../)
* کلاس [String](../../string/)
* کلاس [IFormatProvider](../../iformatprovider/)
* فضای‌نام [System](../../)
* Library [Aspose.Slides](../../../)