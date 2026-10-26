---
title: Presentation()
second_title: Aspose.Slides for C++ API 参考
description: 此构造函数从头创建新的演示文稿。创建的演示文稿包含一个空幻灯片。
type: docs
weight: 417
url: /zh/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() 构造函数

此构造函数从头创建新的演示文稿。创建的演示文稿包含一个空幻灯片。

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) 构造函数

此构造函数从头创建新的演示文稿。创建的演示文稿包含一个空幻灯片。

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | 附加加载选项。 |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) 构造函数

此构造函数是读取现有[Presentation](../)的主要机制。

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 输入流。 |

## 备注

```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) 构造函数

此构造函数是读取现有[Presentation](../)的主要机制。

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 输入流。 |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | 附加加载选项。 |

## Presentation::Presentation(System::String) 构造函数

此构造函数获取源文件路径，以读取[Presentation](../)的内容。

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 输入文件。 |

## 备注

```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) 构造函数

此构造函数获取源文件路径，以读取[Presentation](../)的内容。

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 输入文件。 |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | 附加加载选项。 |

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Presentation](../)
* 类 [LoadOptions](../../loadoptions/)
* 类 [Stream](../../../system.io/stream/)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)