---
title: Compare()
second_title: مرجع API Aspose.Slides برای C++
description: اشیای Uri مشخص‌شده را با استفاده از قوانین مقایسهٔ مشخص‌شده مقایسه می‌کند.
type: docs
weight: 521
url: /fa/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) متد

اشیای [Uri](../) مشخص‌شده را با استفاده از قوانین مقایسهٔ مشخص‌شده مقایسه می‌کند.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | مقایسه‌کنندهٔ اول |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | مقایسه‌کنندهٔ دوم |
| partsToCompare | [UriComponents](../../uricomponents/) | قسمت‌های **uri1** و **uri2** را که باید مقایسه شوند، مشخص می‌کند |
| compareFormat | [UriFormat](../../uriformat/) | Escape کاراکترها را که هنگام مقایسهٔ اجزای URI استفاده می‌شود، مشخص می‌کند |
| comparisonType | [StringComparison](../../stringcomparison/) | یکی از مقادیر StringComparison |

### مقدار بازگشت

یک مقدار منفی اگر **uri1** کمتر از **uri2** باشد؛ 0 اگر uri1 و uri2 برابر باشند؛ یک مقدار مثبت اگر **uri1** بزرگتر از **uri2** باشد

## موارد مرتبط

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* کلاس [Uri](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)