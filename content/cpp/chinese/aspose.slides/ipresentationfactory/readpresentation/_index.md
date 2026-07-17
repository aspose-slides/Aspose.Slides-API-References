---
title: ReadPresentation()
second_title: Aspose.Slides C++ API 参考
description: 从数组读取现有演示文稿
type: docs
weight: 27
url: /zh/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) 方法


从数组读取现有演示文稿

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要读取的数组 |

### 返回值

读取的演示文稿

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) 方法


使用附加加载选项从数组读取现有演示文稿

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要读取的数组 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 加载选项 |

### 返回值

读取的演示文稿

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) 方法


从流读取现有演示文稿

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要读取的输入流 |

### 返回值

读取的演示文稿

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) 方法


使用附加加载选项从流读取现有演示文稿

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要读取的输入流 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 加载选项 |

### 返回值

读取的演示文稿

## IPresentationFactory::ReadPresentation(System::String) 方法


从文件读取现有演示文稿

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 文件名 |

### 返回值

读取的演示文稿

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) 方法


使用附加加载选项从文件读取现有演示文稿

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 文件名 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 加载选项 |

### 返回值

读取的演示文稿

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [IPresentation](../../ipresentation/)
* 类 [IPresentationFactory](../)
* 类 [ILoadOptions](../../iloadoptions/)
* 类 [Stream](../../../system.io/stream/)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)