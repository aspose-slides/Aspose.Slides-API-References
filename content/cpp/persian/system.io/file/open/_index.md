---
title: Open()
second_title: مرجع API Aspose.Slides برای C++
description: فایلی را که مشخص شده است به حالت مشخص شده برای خواندن و نوشتن باز می‌کند و بدون به‌اشتراک‌گذاری.
type: docs
weight: 235
url: /fa/system.io/file/open/
---
## File::Open(const String&, FileMode) متد

فایلی را که مشخص شده است به حالت مشخص شده برای خواندن و نوشتن باز می‌کند و بدون به‌اشتراک‌گذاری است.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیر فایلی که باید باز شود |
| mode | [FileMode](../../filemode/) | حالت باز شدن فایل را مشخص می‌کند |

### مقدار بازگشت

A [FileStream](../../filestream/) object associated with the opened file

## File::Open(const String&, FileMode, FileAccess, FileShare) متد

فایلی را که مشخص شده است به حالت مشخص شده باز می‌کند، با نوع دسترسی مشخص و گزینه به‌اشتراک‌گذاری.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیر فایلی که باید باز شود |
| mode | [FileMode](../../filemode/) | حالت باز شدن فایل را مشخص می‌کند |
| access | [FileAccess](../../fileaccess/) | نوع دسترسی درخواستی |
| share | [FileShare](../../fileshare/) | نوع دسترسی‌ای که سایر اشیاء [FileStream](../../filestream/) به فایل باز شده دارند |

### مقدار بازگشت

A [FileStream](../../filestream/) object associated with the opened file

## موارد مرتبط

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* کلاس [String](../../../system/string/)
* کلاس [File](../)
* فضای‌نام [System::IO](../../)
* Library [Aspose.Slides](../../../)