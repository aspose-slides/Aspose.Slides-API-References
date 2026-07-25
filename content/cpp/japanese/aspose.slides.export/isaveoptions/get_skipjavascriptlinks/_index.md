---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。読み取り専用 bool。デフォルト値は false です。
type: docs
weight: 105
url: /ja/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() メソッド

プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。読み取り専用 **bool**。デフォルト値は **false** です。

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
```

## 備考

このプロパティが **true** に設定されている場合、保存中に JavaScript 呼び出しを含むハイパーリンクは無視されます。

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