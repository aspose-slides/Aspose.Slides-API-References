---
title: GetPresentationText()
second_title: Aspose.Slides C++ API 参考
description: 检索幻灯片中的原始文本
type: docs
weight: 53
url: /zh/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) 方法

检索幻灯片中的原始文本

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 输入文件 |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 提取模式 |

### 返回值

包含表示原始幻灯片文本的 SlideText 数组的 [PresentationText](../../presentationtext/) 实例

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) 方法

检索幻灯片中的原始文本

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 输入流 |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 提取模式 |

### 返回值

包含表示原始幻灯片文本的 SlideText 数组的 [PresentationText](../../presentationtext/) 实例

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) 方法

检索幻灯片中的原始文本

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 输入流 |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 提取模式 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 加载选项 |

### 返回值

包含表示原始幻灯片文本的 SlideText 数组的 [PresentationText](../../presentationtext/) 实例

## See Also

* 枚举 [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPresentationText](../../ipresentationtext/)
* 类 [String](../../../system/string/)
* 类 [PresentationFactory](../)
* 类 [Stream](../../../system.io/stream/)
* 类 [ILoadOptions](../../iloadoptions/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)