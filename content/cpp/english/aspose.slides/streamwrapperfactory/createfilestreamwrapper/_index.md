---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides for C++ API Reference
description: Creates FileStream with the specified path and creation mode.
type: docs
weight: 14
url: /aspose.slides/streamwrapperfactory/createfilestreamwrapper/
---
## StreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) method


Creates FileStream with the specified path and creation mode.

```cpp
System::SharedPtr<IStreamWrapper> Aspose::Slides::StreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode) override
```

## StreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) method


Creates FileStream with the specified path, creation mode, and read/write permission.

```cpp
System::SharedPtr<IStreamWrapper> Aspose::Slides::StreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess) override
```

## See Also

* Enum [FileMode](../../../system.io/filemode/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IStreamWrapper](../../istreamwrapper/)
* Class [String](../../../system/string/)
* Class [StreamWrapperFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)