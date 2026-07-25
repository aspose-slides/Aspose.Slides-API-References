---
title: get_ParagraphFormat()
second_title: Aspose.Slides C++ 用 API リファレンス
description: この段落の書式設定オブジェクトを返します。読み取り専用 IParagraphFormat.
type: docs
weight: 14
url: /ja/aspose.slides/paragraph/get_paragraphformat/
---
## Paragraph::get_ParagraphFormat() メソッド

この段落の書式設定オブジェクトを返します。読み取り専用 [IParagraphFormat](../../iparagraphformat/).

```cpp
System::SharedPtr<IParagraphFormat> Aspose::Slides::Paragraph::get_ParagraphFormat() override
```

## 備考

書式設定オブジェクトには現在の段落に対して定義された書式設定パラメータのみが含まれ、継承されたデータは適用されません。

継承された値を含む有効な値を取得するには、[ParagraphFormat::GetEffective](../../paragraphformat/geteffective/) メソッドを使用してください。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IParagraphFormat](../../iparagraphformat/)
* クラス [Paragraph](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)