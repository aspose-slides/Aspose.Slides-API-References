---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides för C++ API-referens
description: Anger om hyperlänkar med JavaScript-anrop ska hoppas över vid sparande av presentationen. Läs bool. Standardvärdet är false.
type: docs
weight: 105
url: /sv/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() metod


Anger om hyperlänkar med JavaScript-anrop ska hoppas över vid sparande av presentationen. Läs **bool**. Standardvärdet är **false**.

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
```

## Anmärkningar


När denna egenskap är inställd på **true**, kommer hyperlänkar med JavaScript-anrop att ignoreras vid sparande.

När denna egenskap är inställd på **false**, kommer alla hyperlänkar att sparas.

Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Se även

* Klass [ISaveOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)