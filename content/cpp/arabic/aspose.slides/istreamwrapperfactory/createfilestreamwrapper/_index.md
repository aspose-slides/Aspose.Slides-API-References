---
title: CreateFileStreamWrapper()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ FileStream بالمسار المحدد ووضع الإنشاء.
type: docs
weight: 14
url: /ar/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) طريقة

ينشئ FileStream بالمسار المحدد ووضع الإنشاء.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | اسم الملف [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | وضع الملف [System::IO::FileMode](../../../system.io/filemode/) |

### قيمة الإرجاع

مغلّف الدفق لواجهة COM [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) طريقة

ينشئ FileStream بالمسار المحدد، وضع الإنشاء، وصلاحية القراءة/الكتابة.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | اسم الملف [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | وضع الملف [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | صلاحية الملف [System::IO::FileAccess](../../../system.io/fileaccess/) |

### قيمة الإرجاع

مغلّف الدفق لواجهة COM [IStreamWrapper](../../istreamwrapper/)

## انظر أيضًا

* Enum [FileMode](../../../system.io/filemode/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IStreamWrapper](../../istreamwrapper/)
* فئة [String](../../../system/string/)
* فئة [IStreamWrapperFactory](../)
* نطاق الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)