---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides för C++ API-referens
description: Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. Skriv bool. Standardvärdet är false.
type: docs
weight: 118
url: /sv/aspose.slides.export/isaveoptions/set_skipjavascriptlinks/
---
## ISaveOptions::set_SkipJavaScriptLinks(bool) metod


Anger om hyperlänkar med JavaScript-anrop ska hoppas över vid sparande av presentationen. Skriv **bool**. Standardvärdet är **false**.

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_SkipJavaScriptLinks(bool value)=0
```

## Anmärkningar


När denna egenskap är inställd på **true**, hyperlänkar med JavaScript-anrop kommer att ignoreras vid sparande.

När denna egenskap är inställd på **false**, alla hyperlänkar kommer att sparas.

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