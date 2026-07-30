---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. Čte se bool. Výchozí hodnota je false.
type: docs
weight: 105
url: /cs/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() metoda

Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. Čte se **bool**. Výchozí hodnota je **false**.

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
```

## Poznámky

Když je tato vlastnost nastavena na **true**, hypertextové odkazy s voláním JavaScriptu budou při ukládání ignorovány.

Když je tato vlastnost nastavena na **false**, všechny hypertextové odkazy budou uloženy.

Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Viz také

* Třída [ISaveOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)