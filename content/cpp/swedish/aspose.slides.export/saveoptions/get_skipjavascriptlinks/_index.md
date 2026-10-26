---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides för C++ API-referens
description: Anger huruvida hyperlänkar med JavaScript-anrop ska hoppas över vid sparande av presentationen. Läs bool. Standardvärdet är false.
type: docs
weight: 105
url: /sv/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() metod

Anger huruvida hyperlänkar med JavaScript-anrop ska hoppas över vid sparande av presentationen. Läs **bool**. Standardvärdet är **false**.

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
```

## Anmärkningar

När detta egenskap är inställd på **true**, ignoreras hyperlänkar med JavaScript-anrop vid sparande.

När detta egenskap är inställd på **false**, sparas alla hyperlänkar.

Exempel:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Se även

* Klass [SaveOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)