---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。bool を書き込みます。デフォルト値は false です。
type: docs
weight: 118
url: /ja/aspose.slides.export/isaveoptions/set_skipjavascriptlinks/
---
## ISaveOptions::set_SkipJavaScriptLinks(bool) メソッド

プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。**bool** を書き込みます。デフォルト値は **false** です。

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_SkipJavaScriptLinks(bool value)=0
```

## 備考

このプロパティが **true** に設定されている場合、保存時に JavaScript 呼び出しを含むハイパーリンクは無視されます。

このプロパティが **false** に設定されている場合、すべてのハイパーリンクが保存されます。

例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## 参照

* クラス [ISaveOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)