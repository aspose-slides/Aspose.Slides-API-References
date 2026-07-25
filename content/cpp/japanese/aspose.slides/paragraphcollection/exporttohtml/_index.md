---
title: ExportToHtml()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定した段落をHTMLに変換し、Stringオブジェクトとして返します。
type: docs
weight: 170
url: /ja/aspose.slides/paragraphcollection/exporttohtml/
---
## ParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) method


指定した段落をHTMLに変換し、Stringオブジェクトとして返します。

```cpp
System::String Aspose::Slides::ParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | 最初の段落インデックス **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) の数 **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | 変換オプション [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### 戻り値

生成されたHTML。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* クラス [ParagraphCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)