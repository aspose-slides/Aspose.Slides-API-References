---
title: ReadPresentation()
second_title: Aspose.Slides 用于 C++ 的 API 参考
description: 从数组读取现有演示文稿
type: docs
weight: 40
url: /zh/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) 方法

从数组读取现有演示文稿

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要读取的数组 |

### 返回值

读取的演示文稿

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) 方法

从数组读取现有演示文稿并使用额外的加载选项

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要读取的数组 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 加载选项 |

### 返回值

读取的演示文稿

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) 方法

从流读取现有演示文稿

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要读取的输入流 |

### 返回值

读取的演示文稿

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) 方法

从流读取现有演示文稿并使用额外的加载选项

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要读取的输入流 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 加载选项 |

### 返回值

读取的演示文稿

## PresentationFactory::ReadPresentation(System::String) 方法

从文件读取现有演示文稿

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 文件名 |

### 返回值

读取的演示文稿

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) 方法

从流读取现有演示文稿并使用额外的加载选项

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 文件名 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 加载选项 |

### 返回值

读取的演示文稿

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [IPresentation](../../ipresentation/)
* 类 [PresentationFactory](../)
* 类 [ILoadOptions](../../iloadoptions/)
* 类 [Stream](../../../system.io/stream/)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)