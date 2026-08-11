---
title: MakeRelative()
second_title: مرجع API Aspose.Slides برای C++
description: تفاوت بین دو نمونه Uri را تعیین می‌کند.
type: docs
weight: 365
url: /fa/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) متد

تفاوت بین دو نمونه [Uri](../) را تعیین می‌کند.

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI‌ای که با URI فعلی مقایسه می‌شود |

### مقدار برگشتی

اگر نام میزبان و طرح (scheme) URIهایی که توسط شی فعلی و **toUri** نمایندگی می‌شوند یکسان باشند، این متد یک [String](../../string/) را برمی‌گرداند که یک [Uri](../) نسبی را نشان می‌دهد؛ هنگامی که به نمونه URI فعلی افزوده شود، منجر به **toUri** می‌شود. اگر نام میزبان یا طرح متفاوت باشد، این متد یک [String](../../string/) را برمی‌گرداند که پارامتر **uri** را نشان می‌دهد.

## موارد مرتبط

* Typedef [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* کلاس [Uri](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)