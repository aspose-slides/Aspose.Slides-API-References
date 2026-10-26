---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。Read bool. デフォルト値は false です。
type: docs
weight: 105
url: /ja/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() メソッド


プレゼンテーションを保存するときに、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。Read **bool**. デフォルト値は **false** です。

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
```

## 備考


このプロパティが **true** に設定されている場合、JavaScript 呼び出しを含むハイパーリンクは保存時に無視されます。

このプロパティが **false** に設定されている場合、すべてのハイパーリンクが保存されます。

例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## 参照

* クラス [SaveOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)