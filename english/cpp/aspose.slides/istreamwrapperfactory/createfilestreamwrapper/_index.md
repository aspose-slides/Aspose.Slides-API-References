---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides for C++ API Reference
description: Creates FileStream with the specified path and creation mode.
type: docs
weight: 14
url: /cpp/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper([System::String](../../../system/string/), [System::IO::FileMode](../../../system.io/filemode/)) method


Creates FileStream with the specified path and creation mode.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | File name [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | File mode [System::IO::FileMode](../../../system.io/filemode/) |

### Return Value

Stream wrapper for COM interface [IStreamWrapper](../../istreamwrapper/)

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IStreamWrapper](../../istreamwrapper/)
* Class [String](../../../system/string/)
* Enum [FileMode](../../../system.io/filemode/)
* Class [IStreamWrapperFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IStreamWrapperFactory::CreateFileStreamWrapper([System::String](../../../system/string/), [System::IO::FileMode](../../../system.io/filemode/), [System::IO::FileAccess](../../../system.io/fileaccess/)) method


Creates FileStream with the specified path, creation mode, and read/write permission.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | File name [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | File mode [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | File access [System::IO::FileAccess](../../../system.io/fileaccess/) |

### Return Value

Stream wrapper for COM interface [IStreamWrapper](../../istreamwrapper/)

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IStreamWrapper](../../istreamwrapper/)
* Class [String](../../../system/string/)
* Enum [FileMode](../../../system.io/filemode/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Class [IStreamWrapperFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
