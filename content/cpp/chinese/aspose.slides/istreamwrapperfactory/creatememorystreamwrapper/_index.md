---
title: CreateMemoryStreamWrapper()
second_title: Aspose.Slides for C++ API 参考
description: 创建 MemoryStream 包装器。
type: docs
weight: 1
url: /zh/aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() 方法

创建 MemoryStream 包装器。

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```

### 返回值

COM 接口 [IStreamWrapper](../../istreamwrapper/) 的流包装器

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) 方法

根据指定的字节数组创建 MemoryStream 包装器。

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 字节数组 **uint8_t**[] |

### 返回值

COM 接口 [IStreamWrapper](../../istreamwrapper/) 的流包装器

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [IStreamWrapper](../../istreamwrapper/)
* 类 [IStreamWrapperFactory](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)