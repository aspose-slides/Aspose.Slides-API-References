---
title: GetDateTimeFormats()
second_title: مرجع API Aspose.Slides برای C++
description: یک آرایه از رشته‌ها را برمی‌گرداند که هر عنصر، نمایش رشته‌ای از شیء جاری است که با یکی از قالب‌های استاندارد تاریخ و زمان قالب‌بندی شده است.
type: docs
weight: 547
url: /fa/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const متد

یک آرایه از رشته‌ها را برمی‌گرداند که هر عنصر، نمایش رشته‌ای از شیء جاری است که با یکی از قالب‌های استاندارد تاریخ و زمان قالب‌بندی شده است.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const متد

یک آرایه از رشته‌ها را برمی‌گرداند که هر عنصر، نمایش رشته‌ای از شیء جاری است که با قالب استاندارد تاریخ و زمان مشخص شده قالب‌بندی شده است.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| format | char_t | قالب استاندارد تاریخ و زمان. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const متد

یک آرایه از رشته‌ها را برمی‌گرداند که هر عنصر، نمایش رشته‌ای از شیء جاری است که با یکی از قالب‌های استاندارد تاریخ و زمان و با ارائه‌کنندهٔ قالب مشخص‌شده قالب‌بندی شده است.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ارائه‌کنندهٔ قالب. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const متد

یک آرایه از رشته‌ها را برمی‌گرداند که هر عنصر، نمایش رشته‌ای از شیء جاری است که با قالب استاندارد تاریخ و زمان مشخص‌شده و با ارائه‌کنندهٔ قالب قالب‌بندی شده است.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| format | char_t | قالب استاندارد تاریخ و زمان. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ارائه‌کنندهٔ قالب. |

## مراجعه

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTime](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)