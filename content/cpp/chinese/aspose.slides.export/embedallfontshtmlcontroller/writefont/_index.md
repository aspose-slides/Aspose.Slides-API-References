---
title: WriteFont()
second_title: Aspose.Slides for C++ API 参考
description: 将数据以 base64 形式写入 HTML 文档本身
type: docs
weight: 105
url: /zh/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) 方法

将数据以 base64 形式写入 HTML 文档本身

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | HTML 生成器 |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | 要序列化的字体 |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | 被替换的字体（如果发生字体替换），否则为 null |
| fontStyle | [System::String](../../../system/string/) | 字体样式 |
| fontWeight | [System::String](../../../system/string/) | 字体粗细 |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 字体数据 |

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [IHtmlGenerator](../../ihtmlgenerator/)
* 类 [IFontData](../../../aspose.slides/ifontdata/)
* 类 [String](../../../system/string/)
* 类 [EmbedAllFontsHtmlController](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)