---
title: get_DefaultRegularFont()
second_title: Aspose.Slides for C++ API リファレンス
description: "ソース フォントが見つからない場合に使用されるフォントを返します。System::String を読み取ります。"
type: docs
weight: 53
url: /ja/aspose.slides.export/isaveoptions/get_defaultregularfont/
---
## ISaveOptions::get_DefaultRegularFont() メソッド


ソース フォントが見つからない場合に使用されるフォントを返します。[System::String](../../../system/string/) を読み取ります。

```cpp
virtual System::String Aspose::Slides::Export::ISaveOptions::get_DefaultRegularFont()=0
```

## 備考



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto htmlOpts = System::MakeObject<HtmlOptions>();
htmlOpts->set_DefaultRegularFont(u"Arial Black");
pres->Save(u"SomePresentation-out-ArialBlack.html", Aspose::Slides::Export::SaveFormat::Html, htmlOpts);
htmlOpts->set_DefaultRegularFont(u"Lucida Console");
pres->Save(u"Somepresentation-out-LucidaConsole.html", Aspose::Slides::Export::SaveFormat::Html, htmlOpts);

auto pdfOpts = System::MakeObject<PdfOptions>();
pdfOpts->set_DefaultRegularFont(u"Arial Black");
pres->Save(u"SomePresentation-out-ArialBlack.pdf", Aspose::Slides::Export::SaveFormat::Pdf, pdfOpts);
```

## 参照

* クラス [String](../../../system/string/)
* クラス [ISaveOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)