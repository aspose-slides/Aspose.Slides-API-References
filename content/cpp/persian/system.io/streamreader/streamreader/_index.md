---
title: StreamReader()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه از شیء StreamReader می‌سازد که کاراکترها را از جریان زیرین مشخص شده با استفاده از کدگذاری UTF-8 و با بافر با اندازه پیش‌فرض 1024 بایت می‌خواند.
type: docs
weight: 1
url: /fa/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) سازنده

یک نمونه از شیء [StreamReader](../) می‌سازد که کاراکترها را از جریان زیرین مشخص شده با استفاده از کدگذاری UTF-8 و با بافر با اندازه پیش‌فرض 1024 بایت می‌خواند.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | جریان زیرین برای خواندن کاراکترها |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) سازنده

یک نمونه از شیء [StreamReader](../) می‌سازد که کاراکترها را از جریان زیرین مشخص شده با استفاده از کدگذاری UTF-8 و با بافر با اندازه پیش‌فرض 1024 بایت می‌خواند. یک پارامتر تعیین می‌کند که آیا تشخیص علامت ترتیب بایت فعال باشد یا خیر.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | جریان زیرین برای خواندن کاراکترها |
| detectEncodingFromByteOrderMarks | **bool** | در صورتی که می‌خواهید علامت‌های ترتیب بایت را در ابتدای جریان جستجو کنید، True؛ در غیر این صورت false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) سازنده

یک نمونه از شیء [StreamReader](../) می‌سازد که کاراکترها را از جریان زیرین مشخص شده با استفاده از کدگذاری مشخص شده و با بافر با اندازه پیش‌فرض 1024 بایت می‌خواند.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | جریان زیرین برای خواندن کاراکترها |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | کدگذاری مورد استفاده |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) سازنده

یک نمونه از شیء [StreamReader](../) می‌سازد که کاراکترها را از جریان زیرین مشخص شده با استفاده از کدگذاری مشخص شده و با بافر با اندازه پیش‌فرض 1024 بایت می‌خواند. یک پارامتر تعیین می‌کند که آیا تشخیص علامت ترتیب بایت فعال باشد یا خیر.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | جریان زیرین برای خواندن کاراکترها |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | کدگذاری مورد استفاده |
| detectEncodingFromByteOrderMarks | **bool** | در صورتی که می‌خواهید علامت‌های ترتیب بایت را در ابتدای جریان جستجو کنید، True؛ در غیر این صورت false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) سازنده

یک نمونه از شیء [StreamReader](../) می‌سازد که کاراکترها را از جریان زیرین مشخص شده با استفاده از کدگذاری مشخص شده و با بافر با اندازهٔ مشخص می‌خواند. یک پارامتر تعیین می‌کند که آیا تشخیص علامت ترتیب بایت فعال باشد یا خیر.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | جریان زیرین برای خواندن کاراکترها |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | کدگذاری مورد استفاده |
| detectEncodingFromByteOrderMarks | **bool** | در صورتی که می‌خواهید علامت‌های ترتیب بایت را در ابتدای جریان جستجو کنید، True؛ در غیر این صورت false |
| bufferSize | int | حداقل اندازهٔ بافر بر حسب بایت |

## StreamReader::StreamReader(const System::String\&) سازنده

یک نمونه از شیء [StreamReader](../) می‌سازد که کاراکترها را از فایل مشخص شده با استفاده از کدگذاری UTF-8 و با بافر با اندازه پیش‌فرض 4096 بایت می‌خواند.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | مسیر فایلی که کاراکترها از آن خوانده می‌شوند |

## StreamReader::StreamReader(const System::String\&, bool) سازنده

یک نمونه از شیء [StreamReader](../) می‌سازد که کاراکترها را از فایل مشخص شده با استفاده از کدگذاری UTF-8 و با بافر با اندازه پیش‌فرض 4096 بایت می‌خواند. یک پارامتر تعیین می‌کند که آیا تشخیص علامت ترتیب بایت فعال باشد یا خیر.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | مسیر فایلی که کاراکترها از آن خوانده می‌شوند |
| detectEncodingFromByteOrderMarks | **bool** | در صورتی که می‌خواهید علامت‌های ترتیب بایت را در ابتدای فایل جستجو کنید، True؛ در غیر این صورت false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) سازنده

یک نمونه از شیء [StreamReader](../) می‌سازد که کاراکترها را از فایل مشخص شده با استفاده از کدگذاری مشخص شده و با بافر با اندازه پیش‌فرض 4096 بایت می‌خواند.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | مسیر فایلی که کاراکترها از آن خوانده می‌شوند |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | کدگذاری مورد استفاده |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) سازنده

یک نمونه از شیء [StreamReader](../) می‌سازد که کاراکترها را از جریان زیرین مشخص شده با استفاده از کدگذاری مشخص شده و با بافر با اندازه پیش‌فرض 4096 بایت می‌خواند. یک پارامتر تعیین می‌کند که آیا تشخیص علامت ترتیب بایت فعال باشد یا خیر.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | مسیر فایلی که کاراکترها از آن خوانده می‌شوند |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | کدگذاری مورد استفاده |
| detectEncodingFromByteOrderMarks | **bool** | در صورتی که می‌خواهید علامت‌های ترتیب بایت را در ابتدای فایل جستجو کنید، True؛ در غیر این صورت false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) سازنده

یک نمونه از شیء [StreamReader](../) می‌سازد که کاراکترها را از فایل مشخص شده با استفاده از کدگذاری مشخص شده و با بافر با اندازهٔ مشخص می‌خواند. یک پارامتر تعیین می‌کند که آیا تشخیص علامت ترتیب بایت فعال باشد یا خیر.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | مسیر فایلی که کاراکترها از آن خوانده می‌شوند |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | کدگذاری مورد استفاده |
| detectEncodingFromByteOrderMarks | **bool** | در صورتی که می‌خواهید علامت‌های ترتیب بایت را در ابتدای فایل جستجو کنید، True؛ در غیر این صورت false |
| bufferSize | int | حداقل اندازهٔ بافر بر حسب بایت |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)