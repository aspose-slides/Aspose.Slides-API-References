---
title: ReplaceText()
second_title: Aspose.Slides for C++ API 參考文件
description: 將所有指定文字的出現替換為另一個指定的文字。
type: docs
weight: 144
url: /zh-hant/aspose.slides/itextframe/replacetext/
---
## ITextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) method

將所有指定文字的出現替換為另一個指定的文字。

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | 要被替換的字串。 |
| newText | [System::String](../../../system/string/) | 用於替換所有 oldText 出現的字串。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | 文字搜尋選項 [ITextSearchOptions](../../itextsearchoptions/)。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 接收搜尋結果的回呼物件 [IFindResultCallback](../../ifindresultcallback/)。 |

## 備註

以下範例程式碼說明如何將一個指定字串替換為另一個指定字串。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// 將所有獨立的 'the' 出現替換為 '<em><strong>'
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [ITextSearchOptions](../../itextsearchoptions/)
* 類別 [IFindResultCallback](../../ifindresultcallback/)
* 類別 [ITextFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)