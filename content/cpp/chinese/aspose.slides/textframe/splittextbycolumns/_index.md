---
title: SplitTextByColumns()
second_title: Aspose.Slides for C++ API 参考
description: 将 ITextFrame 的文本内容拆分为字符串数组，其中每个元素对应框架内的单独文本列。
type: docs
weight: 144
url: /zh/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() 方法


将 [ITextFrame](../../itextframe/) 的文本内容拆分为字符串数组， 
 where each element corresponds to a separate text column within the frame.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```


### 返回值

字符串数组，其中每个字符串表示特定列的文本内容 
 in the [ITextFrame](../../itextframe/).
## 备注



如果文本框不包含多列，返回的数组将只有一个元素 
 containing the full text. 
 Empty columns will be represented as empty strings in the array. 
下面的示例演示了如何使用 [TextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Get the first shape on the slide and cast it to ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Split the text frame content into columns
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Print each column's text to the console
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [TextFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)