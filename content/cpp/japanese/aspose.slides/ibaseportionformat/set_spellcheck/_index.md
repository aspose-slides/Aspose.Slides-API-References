---
title: set_SpellCheck()
second_title: Aspose.Slides for C++ API リファレンス
description: テキスト部分に対してスペルチェックが有効かどうかを示す値を設定します。このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。true に設定すると、スペルチェックが許可されます。デフォルト値は false です。
type: docs
weight: 612
url: /ja/aspose.slides/ibaseportionformat/set_spellcheck/
---
## IBasePortionFormat::set_SpellCheck(bool) メソッド

テキスト部分に対してスペルチェックが有効かどうかを示す値を設定します。 このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。 true に設定すると、スペルチェックが許可されます。 デフォルト値は **false** です。

```cpp
virtual void Aspose::Slides::IBasePortionFormat::set_SpellCheck(bool value)=0
```

## 備考

次の例は、プレゼンテーションを保存する前に SpellCheck フラグを有効にする方法を示しています: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// 最初のスライドの最初のシェイプ内のテキストの最初の部分にアクセスします
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// このテキスト部分のスペルチェックを有効にします
portion->get_PortionFormat()->set_SpellCheck(true);
// 変更されたプレゼンテーションを保存します
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [IBasePortionFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)