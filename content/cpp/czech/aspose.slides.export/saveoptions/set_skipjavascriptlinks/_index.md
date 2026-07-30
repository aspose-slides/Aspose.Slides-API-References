---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. Zapisujte bool. Výchozí hodnota je false.
type: docs
weight: 118
url: /cs/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) metoda

Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. Zapisujte **bool**. Výchozí hodnota je **false**.

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
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