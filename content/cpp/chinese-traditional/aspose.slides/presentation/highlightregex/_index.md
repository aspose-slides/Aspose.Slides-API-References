---
title: HighlightRegex()
second_title: Aspose.Slides for C++ API 參考文件
description: 以指定的顏色突顯正則表達式的所有匹配項。
type: docs
weight: 508
url: /zh-hant/aspose.slides/presentation/highlightregex/
---
## Presentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) 方法

突顯正則表達式的所有匹配項，使用指定的顏色。

```cpp
void Aspose::Slides::Presentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 正則表達式 [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) 用於取得要突顯的字串。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用於突顯文字的顏色。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 接收搜尋結果 [IFindResultCallback](../../ifindresultcallback/) 的回呼物件。 |
## 備註

以下程式碼示例示範如何使用正則表達式在 PowerPoint [Presentation](../) 中突顯文字。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Regex](../../../system.text.regularexpressions/regex/)
* 類別 [Color](../../../system.drawing/color/)
* 類別 [IFindResultCallback](../../ifindresultcallback/)
* 類別 [Presentation](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)