---
title: Open()
second_title: مرجع API Aspose.Slides برای C++
description: فایلی را که توسط شیء جاری نمایانده شده است در حالت مشخص‌شده برای خواندن و نوشتن و بدون به اشتراک‌گذاری باز می‌کند.
type: docs
weight: 183
url: /fa/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) متد


فایل نمایانگر توسط شیء جاری را در حالت مشخص‌شده برای خواندن و نوشتن و بدون به اشتراک‌گذاری باز می‌کند.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | حالت باز کردن فایل را مشخص می‌کند |

### مقدار بازگشت

یک شیء [FileStream](../../filestream/) مرتبط با فایلی که توسط شیء جاری نمایانده شده است

## FileInfo::Open(FileMode, FileAccess) متد


فایل نمایانگر توسط شیء جاری را در حالت مشخص‌شده، با نوع دسترسی مشخص‌شده و بدون به اشتراک‌گذاری باز می‌کند.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | حالت باز کردن فایل را مشخص می‌کند |
| access | [FileAccess](../../fileaccess/) | نوع دسترسی درخواست‌شده |

### مقدار بازگشت

یک شیء [FileStream](../../filestream/) مرتبط با فایلی که توسط شیء جاری نمایانده شده است

## FileInfo::Open(FileMode, FileAccess, FileShare) متد


فایل نمایانگر توسط شیء جاری را در حالت مشخص‌شده، با نوع دسترسی مشخص‌شده و گزینه به اشتراک‌گذاری باز می‌کند.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | حالت باز کردن فایل را مشخص می‌کند |
| access | [FileAccess](../../fileaccess/) | نوع دسترسی درخواست‌شده |
| share | [FileShare](../../fileshare/) | نوع دسترسی که سایر اشیای [FileStream](../../filestream/) به فایل باز شده دارند |

### مقدار بازگشت

یک شیء [FileStream](../../filestream/) مرتبط با فایلی که توسط شیء جاری نمایانده شده است

## موارد مرتبط

* شمارشی [FileMode](../../filemode/)
* شمارشی [FileAccess](../../fileaccess/)
* شمارشی [FileShare](../../fileshare/)
* تعریف‌نوع [FileStreamPtr](../../../system/filestreamptr/)
* کلاس [FileInfo](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)