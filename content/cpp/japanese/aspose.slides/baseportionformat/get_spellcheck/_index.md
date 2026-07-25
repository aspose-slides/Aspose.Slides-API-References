---
title: get_SpellCheck()
second_title: Aspose.Slides for C++ API リファレンス
description: テキスト部分に対してスペルチェックが有効かどうかを示す値を取得します。このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。true に設定された場合、スペルチェックが許可されます。既定値は false です。
type: docs
weight: 599
url: /ja/aspose.slides/baseportionformat/get_spellcheck/
---
## BasePortionFormat::get_SpellCheck() メソッド


テキスト部分に対してスペルチェックが有効かどうかを示す値を取得します。このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。true に設定された場合、スペルチェックが許可されます。既定値は **false** 。

```cpp
bool Aspose::Slides::BasePortionFormat::get_SpellCheck() override
```

## 備考


次の例は、プレゼンテーションを保存する前に SpellCheck フラグを有効にすることを示します： 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Access the first portion of text inside the first shape on the first slide
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Enable spell checking for this text portion
portion->get_PortionFormat()->set_SpellCheck(true);
// Save the modified presentation
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [BasePortionFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)