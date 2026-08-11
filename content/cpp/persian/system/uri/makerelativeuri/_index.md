---
title: MakeRelativeUri()
second_title: مرجع API Aspose.Slides for C++
description: تفاوت بین URIهایی که توسط شیء جاری و شیء Uri مشخص‌شده نمایان می‌شوند را تعیین می‌کند.
type: docs
weight: 352
url: /fa/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) متد

تفاوت بین URIهای نمایان‌شده توسط شیء جاری و شیء [Uri](../) مشخص‌شده را تعیین می‌کند.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | مقایسه‌گر |

### مقدار بازگشتی

اگر نام میزبان و طرح URIهای نمایان‌شده توسط شیء جاری و **toUri** یکسان باشند، این متد یک [Uri](../) نسبی را برمی‌گرداند که وقتی به نمونه URI جاری افزوده شود، **toUri** را تولید می‌کند. اگر نام میزبان یا طرح متفاوت باشد، این متد یک شیء [Uri](../) را برمی‌گرداند که نمایانگر پارامتر **uri** است.

## موارد مرتبط

* Typedef [SharedPtr](../../sharedptr/)
* کلاس [Uri](../)
* فضای‌نام [System](../../)
* Library [Aspose.Slides](../../../)