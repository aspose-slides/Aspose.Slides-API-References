---
title: SplitTextByColumns()
second_title: Aspose.Slides for C++ API リファレンス
description: ITextFrame のテキストコンテンツを文字列の配列に分割し、各要素はフレーム内の個別のテキスト列に対応します。
type: docs
weight: 118
url: /ja/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() メソッド


[ITextFrame](../) のテキストコンテンツを文字列の配列に分割し、 
 各要素はフレーム内の個別のテキスト列に対応します。

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```


### 戻り値

文字列の配列で、各文字列は 
 [ITextFrame](../) の特定の列のテキストコンテンツを表します。
## 備考



テキストフレームに複数の列が含まれていない場合、返される配列は全体のテキストを含む単一の要素となります。 
 空の列は配列内で空文字列として表されます。 
以下の例は [ITextFrame::SplitTextByColumns](./) の使用方法を示します。 
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

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [ITextFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)