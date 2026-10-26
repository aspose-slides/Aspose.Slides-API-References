---
title: get_HandleRepeatedSpaces()
second_title: Aspose.Slides for C++ API 参考
description: 指定在 Markdown 导出过程中如何处理重复的普通空格字符。
type: docs
weight: 235
url: /zh/aspose.slides.export/markdownsaveoptions/get_handlerepeatedspaces/
---
## MarkdownSaveOptions::get_HandleRepeatedSpaces() const 方法

指定在 Markdown 导出过程中如何处理重复的普通空格字符。

```cpp
Aspose::Slides::Export::HandleRepeatedSpaces Aspose::Slides::Export::MarkdownSaveOptions::get_HandleRepeatedSpaces() const
```

## 备注

此属性定义连续空格的处理方式：

* 保持为普通空格字符，
* 在普通空格和不间断空格实体（**&nbsp;**）之间交替，
* 或在第一个之后全部替换为 **&nbsp;**，以在 Markdown 输出中保持视觉对齐。

默认值为 [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/)。

## 另请参阅

* 枚举 [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* 类 [MarkdownSaveOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)