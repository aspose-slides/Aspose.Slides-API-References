---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert of hyperlinks met JavaScript-roepen moeten worden overgeslagen bij het opslaan van de presentatie. Lezen bool. De standaardwaarde is false.
type: docs
weight: 105
url: /nl/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() methode

Specificeert of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie. Lezen **bool**. De standaardwaarde is **false**.

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
```

## Opmerkingen

Wanneer deze eigenschap is ingesteld op **true**, worden hyperlinks met JavaScript-aanroepen genegeerd tijdens het opslaan.

Wanneer deze eigenschap is ingesteld op **false**, worden alle hyperlinks opgeslagen.

Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Zie ook

* Klasse [SaveOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)