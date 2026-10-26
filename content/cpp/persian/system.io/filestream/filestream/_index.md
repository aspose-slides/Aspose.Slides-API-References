---
title: FileStream()
second_title: Aspose.Slides برای C++ API Reference
description: یک نمونه جدید از کلاس FileStream می‌سازد و آن را با پارامترهای مشخص شده مقداردهی اولیه می‌کند.
type: docs
weight: 1
url: /fa/system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) constructor

یک نمونه جدید از کلاس [FileStream](../) را می‌سازد و آن را با پارامترهای مشخص شده مقداردهی اولیه می‌کند.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیر فایلی که باید باز شود. |
| mode | [FileMode](../../filemode/) | حالت باز کردن فایل را مشخص می‌کند. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) constructor

یک نمونه جدید از کلاس [FileStream](../) را می‌سازد و آن را با پارامترهای مشخص شده مقداردهی اولیه می‌کند.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیر فایلی که باید باز شود. |
| mode | [FileMode](../../filemode/) | حالت باز کردن فایل را مشخص می‌کند. |
| access | [FileAccess](../../fileaccess/) | نوع دسترسی درخواست شده. |
| share | [FileShare](../../fileshare/) | نوع دسترسی‌ای که سایر اشیاء [FileStream](../) به فایل باز شده دارند. |
| buffer_size | **int32_t** | تعداد بایت‌های بافر شده هنگام عملیات خواندن و نوشتن. |
| options | [FileOptions](../../fileoptions/) | گزینه‌های اضافی. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) constructor

یک نمونه جدید از کلاس [FileStream](../) را می‌سازد و آن را با پارامترهای مشخص شده مقداردهی 초기 می‌کند.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیر فایلی که باید باز شود. |
| mode | [FileMode](../../filemode/) | حالت باز کردن فایل را مشخص می‌کند. |
| access | [FileAccess](../../fileaccess/) | نوع دسترسی درخواست شده. |
| share | [FileShare](../../fileshare/) | نوع دسترسی‌ای که سایر اشیاء [FileStream](../) به فایل باز شده دارند. |
| buffer_size | **int32_t** | تعداد بایت‌های بافر شده هنگام عملیات خواندن و نوشتن. |
| useAsync | **bool** | مشخص می‌کند که آیا از I/O ناهمگام یا I/O همگام استفاده شود. |
## توضیحات

سیستم عامل زیرسطح ممکن است از I/O ناهمگام پشتیبانی نکند.

## FileStream::FileStream(const FileStream\&) constructor

```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## موارد مرتبط

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Class [String](../../../system/string/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)