---
title: StreamWriter()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه از شی StreamWriter ایجاد می‌کند که نویسه‌ها را در جریان پایهٔ مشخص‌شده با استفاده از رمزگذاری UTF-8 و یک بافر با اندازه پیش‌فرض 1024 بایت می‌نویسد.
type: docs
weight: 1
url: /fa/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) constructor

یک نمونه از شی [StreamWriter](../) را می‌سازد که با استفاده از رمزگذاری UTF-8 و یک بافر با اندازه پیش‌فرض 1024 بایت، نویسه‌ها را در جریان پایهٔ مشخص‌شده می‌نویسد.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | جریانی که برای نوشتن نویسه‌ها به آن استفاده می‌شود |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor

یک نمونه از شی [StreamWriter](../) را می‌سازد که با استفاده از رمزگذاری مشخص‌شده و یک بافر با اندازه پیش‌فرض 1024 بایت، نویسه‌ها را در جریان پایهٔ مشخص‌شده می‌نویسد.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | جریانی که برای نوشتن نویسه‌ها به آن استفاده می‌شود |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | رمزگذاری مورد استفاده |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) constructor

یک نمونه از شی [StreamWriter](../) را می‌سازد که با استفاده از رمزگذاری مشخص‌شده و بافر با اندازهٔ مشخص، نویسه‌ها را در جریان پایهٔ مشخص‌شده می‌نویسد. یک پارامتر تعیین می‌کند که آیا جریان پایه هنگام آزاد شدن شی [StreamWriter](../) باید بسته شود یا خیر.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | جریانی که برای نوشتن نویسه‌ها به آن استفاده می‌شود |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | رمزگذاری مورد استفاده |
| buffer_size | int | حداقل اندازه بافر برحسب بایت |
| leave_open | **bool** | تعیین می‌کند که آیا جریان پایه پس از آزاد شدن شی [StreamWriter](../) باز بماند یا خیر |

## StreamWriter::StreamWriter(const String\&) constructor

یک نمونه از شی [StreamWriter](../) را می‌سازد که با استفاده از رمزگذاری UTF-8 و یک بافر با اندازه پیش‌فرض 1024 بایت، نویسه‌ها را در فایل مشخص‌شده می‌نویسد.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیری که فایل برای نوشتن نویسه‌ها به آن استفاده می‌شود |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) constructor

یک نمونه از شی [StreamWriter](../) را می‌سازد که با استفاده از رمزگذاری مشخص‌شده و یک بافر با اندازه پیش‌فرض 1024 بایت، نویسه‌ها را در فایل مشخص‌شده می‌نویسد. یک پارامتر تعیین می‌کند که آیا داده‌ها باید به فایل اضافه شوند یا فایل بازنویسی شود.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیری که فایل برای نوشتن نویسه‌ها به آن استفاده می‌شود |
| append | **bool** | تعیین می‌کند که آیا داده باید به فایل مشخص‌شده اضافه شود (true) یا فایل بازنویسی شود (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | رمزگذاری مورد استفاده |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) constructor

یک نمونه از شی [StreamWriter](../) را می‌سازد که با استفاده از رمزگذاری مشخص‌شده و با اندازهٔ بافر، نویسه‌ها را در فایل مشخص‌شده می‌نویسد. یک پارامتر تعیین می‌کند که آیا داده‌ها باید به فایل اضافه شوند یا فایل بازنویسی شود.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیری که فایل برای نوشتن نویسه‌ها به آن استفاده می‌شود |
| append | **bool** | تعیین می‌کند که آیا داده باید به فایل مشخص‌شده اضافه شود (true) یا فایل بازنویسی شود (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | رمزگذاری مورد استفاده |
| buffer_size | int | اندازه بافری که استفاده می‌شود |

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* کلاس [Stream](../../stream/)
* کلاس [StreamWriter](../)
* کلاس [String](../../../system/string/)
* فضای نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)