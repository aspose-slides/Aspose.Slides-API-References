---
title: MemoryStream()
second_title: Aspose.Slides برای C++ مرجع API
description: یک نمونه جدید از کلاس MemoryStream را با ظرفیت اولیه برابر با ۰ می‌سازد.
type: docs
weight: 1
url: /fa/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() سازنده

یک نمونهٔ جدید از کلاس [MemoryStream](../) با ظرفیت اولیه برابر با ۰ می‌سازد.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) سازنده

یک نمونهٔ جدید از کلاس [MemoryStream](../) که نمایانگر یک جریان مبتنی بر بافر حافظه با اندازهٔ مشخص است، می‌سازد.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| capacity_ | int | اندازه به بایت‌های بافر حافظه مرتبط با جریان که توسط شیء در حال ساخت نمایندگی می‌شود |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) سازنده

یک نمونهٔ جدید از کلاس [MemoryStream](../) که نمایانگر یک جریان حافظه متصل به بافر حافظهٔ مشخص است، می‌سازد. یک پارامتر مشخص می‌کند آیا جریان قابل نوشتن است یا نه.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایهٔ بایتی که به عنوان بافر حافظه استفاده می‌شود و جریان نمایانده شده توسط شیء در حال ساخت بر پایهٔ آن خواهد بود |
| writable | **bool** | مشخص می‌کند آیا جریان باید قابل نوشتن باشد |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) سازنده

یک نمونهٔ جدید از کلاس [MemoryStream](../) که نمایانگر یک جریان حافظه متصل به بخشی از بافر حافظهٔ مشخص، شروع از اندیس معین و شامل تعداد معینی از عناصر است، می‌سازد. پارامترها مشخص می‌کنند آیا جریان قابل نوشتن است و آیا می‌توان متد GetBytes() را فراخوانی کرد.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایهٔ بایتی که بخشی از آن به عنوان بافر حافظه استفاده می‌شود و جریان نمایانده شده توسط شیء در حال ساخت بر پایهٔ آن خواهد بود |
| index | int | اندیس ۰-پایهٔ عنصر در **content** که بخش از آن آغاز می‌شود |
| count | int | تعداد عناصر **content** که در بخش گنجانده شده‌اند |
| writable | **bool** | مشخص می‌کند آیا جریان باید قابل نوشتن باشد |
| publiclyVisible | **bool** | مشخص می‌کند آیا بافر حافظهٔ زیرین باید برای فراخوانندهٔ متد GetByte() قابل دسترسی باشد |

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)