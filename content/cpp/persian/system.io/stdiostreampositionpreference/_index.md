---
title: STDIOStreamPositionPreference
second_title: مرجع API Aspose.Slides برای C++
description: "تعیین می‌کند که کدام موقعیت در جریان به‌عنوان موقعیت مشترک خواندن و نوشتن ترجیح داده می‌شود وقتی std::basic_iostream و مشتق‌های آن در زمان ایجاد رِپر، موقعیت‌های متفاوتی برای خواندن و نوشتن داشته باشند."
type: docs
weight: 586
url: /fa/system.io/stdiostreampositionpreference/
---
## STDIOStreamPositionPreference enum

تعیین می‌کند کدام موقعیت در جریان به‌عنوان موقعیت مشترک خواندن و نوشتن ترجیح داده می‌شود وقتی `std::basic_iostream` و مشتق‌های آن در زمان ایجاد رِپر، موقعیت‌های متفاوتی برای خواندن و نوشتن داشته باشند.

```cpp
enum class STDIOStreamPositionPreference
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| Zero | 0 | موقعیت صفر به عنوان موقعیت خواندن و نوشتن تنظیم می‌شود. |
| ReadPosition | 1 | موقعیت gptr به عنوان موقعیت خواندن و نوشتن تنظیم می‌شود. |
| WritePosition | 2 | موقعیت pptr به عنوان موقعیت خواندن و نوشتن تنظیم می‌شود. |

## مراجع

* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)