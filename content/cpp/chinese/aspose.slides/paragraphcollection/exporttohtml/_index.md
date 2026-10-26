---
title: ExportToHtml()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的段落转换为 HTML，并以 String 对象返回。
type: docs
weight: 170
url: /zh/aspose.slides/paragraphcollection/exporttohtml/
---
## ParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) 方法

将指定的段落转换为 HTML 并返回为 String 对象。

```cpp
System::String Aspose::Slides::ParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | 首个段落索引 **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) 计数 **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | 转换选项 [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### 返回值

生成的 HTML。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* 类 [ParagraphCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)