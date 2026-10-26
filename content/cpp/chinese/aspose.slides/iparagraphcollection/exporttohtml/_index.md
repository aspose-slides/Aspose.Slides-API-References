---
title: ExportToHtml()
second_title: Aspose.Slides C++ API 参考
description: 将指定的段落转换为 HTML，并返回为 String 对象。
type: docs
weight: 105
url: /zh/aspose.slides/iparagraphcollection/exporttohtml/
---
## IParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) 方法

将指定的段落转换为 HTML 并返回为 String 对象。

```cpp
virtual System::String Aspose::Slides::IParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | 第一个段落索引 **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) 计数 **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | 转换选项 [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### 返回值

生成的 HTML。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* 类 [IParagraphCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)