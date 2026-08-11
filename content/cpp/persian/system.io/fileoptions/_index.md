---
title: FileOptions
second_title: مرجع API Aspose.Slides برای C++
description: گزینه‌های پیشرفته برای ایجاد شیء FileStream را نشان می‌دهد.
type: docs
weight: 521
url: /fa/system.io/fileoptions/
---
## FileOptions enum

گزینه‌های پیشرفته برای ایجاد شیء [FileStream](../filestream/) را نشان می‌دهد.

```cpp
enum class FileOptions
```

### Values

| نام | مقدار | توضیح |
| --- | --- | --- |
| None | 0 | بدون گزینه‌های اضافی. |
| Encrypted | 16384 | فایل رمزنگاری شده است. پیاده‌سازی نشده. |
| DeleteOnClose | 67108864 | فایل باید به‌صورت خودکار زمانی که دیگر استفاده نمی‌شود، حذف شود. |
| SequentialScan | 134217728 | فایل باید به‌صورت ترتیبی مورد دسترسی قرار گیرد. |
| RandomAccess | 268435456 | دسترسی به فایل به‌صورت تصادفی است. |
| Asynchronous | 1073741824 | فایل می‌تواند برای عملیات I/O ناهمزمان استفاده شود. |
| WriteThrough | n/a | تمام نوشتارها باید مستقیماً به دیسک انجام شوند و از هر کش میانی عبور نکنند. |

## موارد مرتبط

* فضای‌نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)