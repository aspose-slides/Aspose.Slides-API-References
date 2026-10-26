---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides برای C++ مرجع API
description: یک FileStream را با مسیر و حالت ایجاد مشخص‌شده ایجاد می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) متد

FileStream را با مسیر و حالت ایجاد مشخص‌شده ایجاد می‌کند.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | نام فایل [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | حالت فایل [System::IO::FileMode](../../../system.io/filemode/) |

### مقدار بازگشتی

غلاف جریان برای رابط COM [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) متد

FileStream را با مسیر، حالت ایجاد و دسترسی خواندن/نوشتن مشخص‌شده ایجاد می‌کند.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | نام فایل [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | حالت فایل [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | دسترسی فایل [System::IO::FileAccess](../../../system.io/fileaccess/) |

### مقدار بازگشتی

غلاف جریان برای رابط COM [IStreamWrapper](../../istreamwrapper/)

## موارد مرتبط

* enum [FileMode](../../../system.io/filemode/)
* enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IStreamWrapper](../../istreamwrapper/)
* کلاس [String](../../../system/string/)
* کلاس [IStreamWrapperFactory](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)