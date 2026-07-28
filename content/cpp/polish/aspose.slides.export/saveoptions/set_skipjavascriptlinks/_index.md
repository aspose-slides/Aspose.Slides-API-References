---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Zapisz bool. Wartość domyślna to false.
type: docs
weight: 118
url: /pl/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) metoda


Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Zapisz **bool**. Wartość domyślna to **false**.

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
```

## Uwagi


Gdy ta właściwość ma wartość **true**, hiperłącza z wywołaniami JavaScript będą pomijane podczas zapisywania.

Gdy ta właściwość ma wartość **false**, wszystkie hiperłącza zostaną zapisane.

Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Zobacz także

* Klasa [SaveOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)