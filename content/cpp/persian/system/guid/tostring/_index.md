---
title: ToString()
second_title: Aspose.Slides برای C++ مرجع API
description: GUID نمایان‌شده توسط شیء جاری را به نمایش رشته‌ای آن تبدیل می‌کند.
type: docs
weight: 79
url: /fa/system/guid/tostring/
---
## Guid::ToString() const متد

GUID نمایندهٔ شیء جاری را به نمایش رشته‌ای آن تبدیل می‌کند.

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const متد

GUID نمایندهٔ شیء جاری را با استفاده از قالب رشته‌ای مشخص به نمایش رشته‌ای آن تبدیل می‌کند.

```cpp
String System::Guid::ToString(const String &format) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| format | const [String](../../string/)\& | قالب مورد استفاده |

### مقدار بازگشتی

نمایش رشته‌ای مقدار GUID که توسط شیء جاری نمایانده شده است

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const متد

GUID نمایندهٔ شیء جاری را با استفاده از قالب رشته‌ای مشخص و فرهنگ موردنظر به نمایش رشته‌ای آن تبدیل می‌کند.

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| format | const [String](../../string/)\& | قالب مورد استفاده |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | فرهنگ مورد استفاده |

### مقدار بازگشتی

نمایش رشته‌ای مقدار GUID که توسط شیء جاری نمایانده شده است

## همچنین ببینید

* Typedef [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* کلاس [Guid](../)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)