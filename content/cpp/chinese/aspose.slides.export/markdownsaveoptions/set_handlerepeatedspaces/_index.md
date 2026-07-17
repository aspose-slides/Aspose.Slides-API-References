---
title: set_HandleRepeatedSpaces()
second_title: Aspose.Slides C++ API 参考
description: 指定在 Markdown 导出期间如何处理重复的普通空格字符。
type: docs
weight: 248
url: /zh/aspose.slides.export/markdownsaveoptions/set_handlerepeatedspaces/
---
## MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces) 方法

指定在 Markdown 导出期间如何处理重复的普通空格字符。

```cpp
void Aspose::Slides::Export::MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces value)
```

## 备注

此属性定义连续空格的处理方式，可为：
* 保持为普通空格字符，
* 在普通空格和不间断空格实体（**&nbsp;**）之间交替，
* 或在第一个之后全部替换为 **&nbsp;** 以在 Markdown 输出中保持视觉对齐。

默认值为 [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/)。 
## 另请参阅

* 枚举 [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* 类 [MarkdownSaveOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)