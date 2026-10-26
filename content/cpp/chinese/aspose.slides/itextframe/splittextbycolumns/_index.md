---
title: SplitTextByColumns()
second_title: Aspose.Slides C++ API 参考
description: 将 ITextFrame 的文本内容拆分为字符串数组，每个元素对应框架中的单独文本列。
type: docs
weight: 118
url: /zh/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() 方法


将 [ITextFrame](../) 的文本内容拆分为字符串数组，

每个元素对应框架内的单独文本列。

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```

### 返回值

一个字符串数组，其中每个字符串表示特定列的文本内容，

在 [ITextFrame](../) 中。

## 备注

如果文本框不包含多列，返回的数组将只有一个元素

其中包含完整的文本。

空列将在数组中表示为空字符串。

下面的示例演示如何使用 [ITextFrame::SplitTextByColumns](./)：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// 获取幻灯片上的第一个形状并将其转换为 ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// 将文本框内容拆分为列
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// 将每列的文本打印到控制台
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [ITextFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)