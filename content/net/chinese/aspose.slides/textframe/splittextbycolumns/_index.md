---
title: SplitTextByColumns
second_title: Aspose.Slides for .NET API Reference
description: 将ITextFrameaspose.slides/itextframe的文本内容拆分成字符串数组，其中每个元素对应于框架内的单独文本列。
type: docs
weight: 140
url: /zh/aspose.slides/textframe/splittextbycolumns/
---

## TextFrame.SplitTextByColumns 方法

将[`ITextFrame`](../../itextframe)的文本内容拆分为字符串数组，其中每个元素对应框架内的单独文本列。

```csharp
public string[] SplitTextByColumns()
```

### 返回值

一个字符串数组，其中每个字符串表示[`ITextFrame`](../../itextframe)中特定列的文本内容。

### 备注

如果文本框架不包含多个列，则返回的数组将只有一个元素，包含完整文本。空列将在数组中表示为空字符串。

### 示例

以下示例演示如何使用`SplitTextByColumns`：

```csharp
using (Presentation pres = new Presentation("example.pptx"))
{
    // 获取幻灯片上的第一个形状并将其转换为ITextFrame
    ITextFrame textFrame = pres.Slides[0].Shapes[0] as ITextFrame;
    // 将文本框内容拆分为列
    string[] columnsText = textFrame.SplitTextByColumns();
    // 将每列的文本打印到控制台
    foreach (string column in columnsText)
        Console.WriteLine(column);
}
```

### 另请参阅

* class [TextFrame](../../textframe)
* namespace [Aspose.Slides](../../textframe)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->