---
title: ToString()
second_title: مرجع API Aspose.Slides برای C++
description: نمایش رشته‌ای مقدار نمایان شده توسط شیء را باز می‌گرداند.
type: docs
weight: 352
url: /fa/system/decimal/tostring/
---
## Decimal::ToString() const متد

نمایش string رشته‌ای مقدار نمایان شده توسط شیء را باز می‌گرداند.

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const متد

شیء جاری را به رشته تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ.

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [IFormatProvider](../../iformatprovider/) شیء که اطلاعات قالب‌بندی مخصوص فرهنگ را فراهم می‌کند. |

### مقدار بازگشت

نمایش string شیء جاری.

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const متد




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const متد




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const متد




```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const متد

شیء جاری را به نمایش رشته‌ای خود تبدیل می‌کند با استفاده از قالب رشته‌ای مشخص و اطلاعات قالب‌بندی مخصوص فرهنگ ارائه‌شده توسط شیء [IFormatProvider](../../iformatprovider/) مشخص‌شده.

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| format | const [String](../../string/)\& | قالب string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [IFormatProvider](../../iformatprovider/) شیء که اطلاعات قالب‌بندی مخصوص فرهنگ را فراهم می‌کند. |

### مقدار بازگشت

نمایش string شیء جاری.

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const متد




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const متد




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const متد




```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* کلاس [Decimal](../)
* کلاس [IFormatProvider](../../iformatprovider/)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* کلاس [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)