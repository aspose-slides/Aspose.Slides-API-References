---
title: ToString()
second_title: Aspose.Slides برای مرجع API C++
description: رشتهٔ نمایانگر مقدار تاریخ و زمان که توسط شیء جاری نمایش داده می‌شود را با استفاده از قواعد قالب‌بندی تعریف‌شده توسط فرهنگ فعلی برمی‌گرداند.
type: docs
weight: 482
url: /fa/system/datetime/tostring/
---
## DateTime::ToString() const متد

رشتهٔ نمایانگر مقدار تاریخ و زمان که توسط شیء جاری نشان داده می‌شود را با استفاده از قواعد قالب‌بندی تعریف‌شده توسط فرهنگ فعلی برمی‌گرداند.

```cpp
String System::DateTime::ToString() const
```

### مقدار بازگشت

رشتهٔ نمایانگر مقدار نمایان‌شده توسط شیء جاری

## DateTime::ToString(const String\&) const متد

رشتهٔ نمایانگر مقدار تاریخ و زمان که توسط شیء جاری نشان داده می‌شود را با استفاده از قالب مشخص‌شده و قواعد قالب‌بندی تعریف‌شده توسط فرهنگ فعلی برمی‌گرداند.

```cpp
String System::DateTime::ToString(const String &format) const
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../../string/)\& | یک رشتهٔ قالب |

### مقدار بازگشت

رشتهٔ نمایانگر مقدار نمایان‌شده توسط شیء جاری که بر اساس قالب تعریف‌شده توسط **format** و فرهنگ فعلی قالب‌بندی شده است.

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const متد

رشتهٔ نمایانگر مقدار تاریخ و زمان که توسط شیء جاری نشان داده می‌شود را با استفاده از اطلاعات قالب مشخص‌شده برمی‌گرداند.

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | یک شیء که اطلاعات قالب را نمایندگی می‌کند |

### مقدار بازگشت

رشتهٔ نمایانگر مقدار نمایان‌شده توسط شیء جاری که بر اساس اطلاعات قالب ارائه‌شده توسط **formatProvider** قالب‌بندی شده است.

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const متد




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const متد




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const متد




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const متد

رشتهٔ نمایانگر مقدار تاریخ و زمان که توسط شیء جاری نشان داده می‌شود را با استفاده از اطلاعات قالب مشخص‌شده برمی‌گرداند.

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../../string/)\& | یک رشتهٔ قالب |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | یک شیء که اطلاعات قالب را نمایندگی می‌کند |

### مقدار بازگشت

رشتهٔ نمایانگر مقدار نمایان‌شده توسط شیء جاری که بر اساس اطلاعات قالب ارائه‌شده توسط **provider** و رشتهٔ قالب **format** قالب‌بندی شده است.

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const متد




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const متد




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const متد




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## مراجع

* Typedef [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* کلاس [DateTime](../)
* کلاس [IFormatProvider](../../iformatprovider/)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* کلاس [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* فضای‌نام [System](../../)
* Library [Aspose.Slides](../../../)