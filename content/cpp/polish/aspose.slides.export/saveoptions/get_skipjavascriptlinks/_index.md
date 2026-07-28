---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Odczyt bool. Domyślna wartość to false.
type: docs
weight: 105
url: /pl/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() metoda


Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Odczyt **bool**. Domyślna wartość to **false**.

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
```

## Uwagi


Gdy ta właściwość ma wartość **true**, hiperłącza z wywołaniami JavaScript będą ignorowane podczas zapisywania.

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