---
title: SplitTextByColumns()
second_title: Aspose.Slides for C++ API リファレンス
description: ITextFrame のテキストコンテンツを文字列の配列に分割し、各要素はフレーム内の個別のテキスト列に対応します。
type: docs
weight: 144
url: /ja/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() メソッド

[ITextFrame](../../itextframe/) のテキストコンテンツを文字列の配列に分割し、  
 各要素はフレーム内の個別のテキスト列に対応します。

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```


### 戻り値

特定の列のテキストコンテンツを表す文字列の配列で、  
 [ITextFrame](../../itextframe/) 内にあります。

## 備考


テキストフレームに複数列が含まれていない場合、返される配列は単一の要素を持ち、  
 完全なテキストを含みます。 

 空の列は配列内で空文字列として表されます。 

以下の例は [TextFrame::SplitTextByColumns](./) の使い方を示しています: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// スライド上の最初のシェイプを取得し、ITextFrame にキャストします
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// テキストフレームのコンテンツを列に分割します
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// 各列のテキストをコンソールに出力します
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## 関連項目

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [TextFrame](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)