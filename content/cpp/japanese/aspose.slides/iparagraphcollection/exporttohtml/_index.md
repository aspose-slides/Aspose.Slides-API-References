---
title: ExportToHtml()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定した段落を HTML に変換し、String オブジェクトとして返します。
type: docs
weight: 105
url: /ja/aspose.slides/iparagraphcollection/exporttohtml/
---
## IParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) メソッド

指定した段落を HTML に変換し、String オブジェクトとして返します。

```cpp
virtual System::String Aspose::Slides::IParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | 最初の段落インデックス **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) カウント **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | 変換オプション [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### 戻り値

生成された HTML。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* クラス [IParagraphCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)