---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides pro C++ - reference API
description: Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. Čtení bool. Výchozí hodnota je false.
type: docs
weight: 105
url: /cs/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() metoda

Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. Čtení **bool**. Výchozí hodnota je **false**.

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
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

* Třída [SaveOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)