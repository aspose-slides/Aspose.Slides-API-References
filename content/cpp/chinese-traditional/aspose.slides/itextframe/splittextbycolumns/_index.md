---
title: SplitTextByColumns()
second_title: Aspose.Slides C++ API 參考
description: 將 ITextFrame 的文字內容分割成字串陣列，每個元素對應框架內的單獨文字欄位。
type: docs
weight: 118
url: /zh-hant/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() 方法


將 [ITextFrame](../) 的文字內容分割成字串陣列， 
 每個元素對應框架內的單獨文字欄位。

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```


### 返回值

字串陣列，其中每個字串代表特定欄位的文字內容 
 在 [ITextFrame](../) 中。


## 備註



如果文字框未包含多個欄位，返回的陣列將僅有一個元素 
 包含完整的文字。 
 空的欄位將在陣列中以空字串表示。 
以下範例說明如何使用 [ITextFrame::SplitTextByColumns](./)： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// 取得投影片上的第一個圖形並將其轉型為 ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// 將文字框內容分割成欄位
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// 將每個欄位的文字輸出至主控台
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [ITextFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)