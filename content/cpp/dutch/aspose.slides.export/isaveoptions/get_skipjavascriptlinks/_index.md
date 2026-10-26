---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides voor C++ API Referentie
description: Specificeert of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie. Lees bool. De standaardwaarde is false.
type: docs
weight: 105
url: /nl/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() methode


Specificeert of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie. Lezen **bool**. De standaardwaarde is **false**.

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
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

* Klasse [ISaveOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)