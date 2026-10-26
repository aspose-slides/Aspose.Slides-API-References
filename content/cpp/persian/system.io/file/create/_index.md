---
title: Create()
second_title: مرجع API Aspose.Slides برای C++
description: فایلی جدید ایجاد می‌کند (یا فایل موجود را بازنویسی می‌کند) و آن را برای دسترسی خواندن و نوشتن با استفاده از اندازه بافر و گزینه‌های مشخص‌شده باز می‌کند.
type: docs
weight: 53
url: /fa/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) متد

یک فایل جدید ایجاد می‌کند (یا فایل موجود را بازنویسی می‌کند) و آن را برای دسترسی خواندن و نوشتن با استفاده از اندازه بافر و گزینه‌های مشخص‌شده باز می‌کند.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیر فایلی که باید ایجاد یا بازنویسی شود |
| bufferSize | **int32_t** | تعداد بایت‌های بافر شده هنگام خواندن و نوشتن به فایل |
| options | [FileOptions](../../fileoptions/) | نحوه ایجاد یا بازنویسی فایل را مشخص می‌کند |

### مقدار بازگشت

یک اشاره‌گر اشتراکی به شیء [FileStream](../../filestream/) مرتبط با فایل مشخص‌شده.

## همچنین ببینید

* شمارشی [FileOptions](../../fileoptions/)
* تعریف-نوع [FileStreamPtr](../../../system/filestreamptr/)
* کلاس [String](../../../system/string/)
* کلاس [File](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)