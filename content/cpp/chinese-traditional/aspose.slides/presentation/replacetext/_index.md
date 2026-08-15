---
title: ReplaceText()
second_title: Aspose.Slides for C++ API 參考
description: 將指定文字的所有出現取代為另一個指定的文字。
type: docs
weight: 521
url: /zh-hant/aspose.slides/presentation/replacetext/
---
## Presentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) 方法

將所有指定文字的出現取代為另一個指定的文字。

```cpp
void Aspose::Slides::Presentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | 要被取代的字串。 |
| newText | [System::String](../../../system/string/) | 用來取代 oldText 所有出現的字串。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | 文字搜尋選項 [ITextSearchOptions](../../itextsearchoptions/)。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 接收搜尋結果的回呼物件 [IFindResultCallback](../../ifindresultcallback/)。 |

## 備註

下列範例程式碼展示如何將一個指定的字串取代為另一個指定的字串。

```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// 將所有獨立的 'the' 出現取代為 '<em><strong>'
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [ITextSearchOptions](../../itextsearchoptions/)
* 類別 [IFindResultCallback](../../ifindresultcallback/)
* 類別 [Presentation](../)
* 名稱空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)