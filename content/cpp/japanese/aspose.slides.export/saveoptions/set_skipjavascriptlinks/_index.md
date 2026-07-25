---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションを保存するときに、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。書き込みは bool。既定値は falseです。
type: docs
weight: 118
url: /ja/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) メソッド

プレゼンテーションを保存するときに、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。書き込みは **bool**。既定値は **false**。

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
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

## 関連項目

* クラス [SaveOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)