---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides för C++ API-referens
description: Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. Skriv bool. Standardvärdet är false.
type: docs
weight: 118
url: /sv/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) method


Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. Skriv **bool**. Standardvärdet är **false**.

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
```

## Anmärkningar


När denna egenskap är satt till **true** kommer hyperlänkar med JavaScript-anrop att ignoreras vid sparande.

När denna egenskap är satt till **false** kommer alla hyperlänkar att sparas.

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