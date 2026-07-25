---
title: HighlightRegex()
second_title: Aspose.Slides for C++ API リファレンス
description: 正規表現のすべての一致を指定された色でハイライトします。
type: docs
weight: 469
url: /ja/aspose.slides/ipresentation/highlightregex/
---
## IPresentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method

指定された色で正規表現のすべての一致をハイライトします。

```cpp
virtual void Aspose::Slides::IPresentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | ハイライトする文字列を取得するための正規表現 [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | テキストをハイライトする色。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 検索結果 [IFindResultCallback](../../ifindresultcallback/) を受け取るためのコールバックオブジェクト。 |

## 備考

正規表現を使用して PowerPoint [Presentation](../../presentation/) のテキストをハイライトする方法を示すコードサンプルです。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## 参考

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Regex](../../../system.text.regularexpressions/regex/)
* クラス [Color](../../../system.drawing/color/)
* クラス [IFindResultCallback](../../ifindresultcallback/)
* クラス [IPresentation](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)