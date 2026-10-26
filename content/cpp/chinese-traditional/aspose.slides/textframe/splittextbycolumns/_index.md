---
title: SplitTextByColumns()
second_title: Aspose.Slides for C++ API 參考
description: 將 ITextFrame 的文字內容分割成字串陣列，每個元素對應框架內的單獨文字欄。
type: docs
weight: 144
url: /zh-hant/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() 方法

將 [ITextFrame](../../itextframe/) 的文字內容分割成字串陣列， 
 每個元素對應框架內的單獨文字欄。

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```

### 回傳值

字串陣列，其中每個字串代表特定欄位的文字內容 
 在 [ITextFrame](../../itextframe/) 中。

## 備註

如果文字框不包含多個欄位，回傳的陣列將只有一個元素 
 包含完整的文字。 
空的欄位將在陣列中以空字串表示。 
以下範例說明如何使用 [TextFrame::SplitTextByColumns](./)： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// 取得投影片上的第一個圖形並將其轉型為 ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// 將文字框內容分割成欄位
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// 將每個欄位的文字列印至主控台
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [TextFrame](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)