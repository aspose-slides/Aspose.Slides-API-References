---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的路径和创建模式创建 FileStream。
type: docs
weight: 14
url: /zh/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) 方法

使用指定的路径和创建模式创建 FileStream。

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | 文件名 [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | 文件模式 [System::IO::FileMode](../../../system.io/filemode/) |

### 返回值

COM 接口的流包装器 [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) 方法

使用指定的路径、创建模式和读/写权限创建 FileStream。

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | 文件名 [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | 文件模式 [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | 文件访问 [System::IO::FileAccess](../../../system.io/fileaccess/) |

### 返回值

COM 接口的流包装器 [IStreamWrapper](../../istreamwrapper/)

## 另请参见

* Enum [FileMode](../../../system.io/filemode/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IStreamWrapper](../../istreamwrapper/)
* Class [String](../../../system/string/)
* Class [IStreamWrapperFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)