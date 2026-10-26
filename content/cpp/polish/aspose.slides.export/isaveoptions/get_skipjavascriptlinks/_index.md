---
title: get_SkipJavaScriptLinks()
second_title: Dokumentacja API Aspose.Slides dla C++
description: Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Odczyt bool. Domyślna wartość to false.
type: docs
weight: 105
url: /pl/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() metoda


Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Odczyt **bool**. Domyślna wartość to **false**.

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
```

## Uwagi


Gdy ta właściwość jest ustawiona na **true**, hiperłącza z wywołaniami JavaScript będą ignorowane podczas zapisywania.

Gdy ta właściwość jest ustawiona na **false**, wszystkie hiperłącza zostaną zapisane.

Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Zobacz także

* Klasa [ISaveOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)