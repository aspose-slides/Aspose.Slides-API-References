---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert of hyperkoppelingen met JavaScript-aanroepen overgeslagen moeten worden bij het opslaan van de presentatie. Schrijf bool. De standaardwaarde is false.
type: docs
weight: 118
url: /nl/aspose.slides.export/isaveoptions/set_skipjavascriptlinks/
---
## ISaveOptions::set_SkipJavaScriptLinks(bool) methode

Specificeert of hyperkoppelingen met JavaScript-aanroepen overgeslagen moeten worden bij het opslaan van de presentatie. Schrijf **bool**. De standaardwaarde is **false**.

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_SkipJavaScriptLinks(bool value)=0
```

## Opmerkingen

Wanneer deze eigenschap is ingesteld op **true**, worden hyperkoppelingen met JavaScript-aanroepen genegeerd tijdens het opslaan.

Wanneer deze eigenschap is ingesteld op **false**, worden alle hyperkoppelingen opgeslagen.

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