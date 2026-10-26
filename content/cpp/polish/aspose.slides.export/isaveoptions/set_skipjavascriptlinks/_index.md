---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Zapisz bool. Domyślna wartość to false.
type: docs
weight: 118
url: /pl/aspose.slides.export/isaveoptions/set_skipjavascriptlinks/
---
## ISaveOptions::set_SkipJavaScriptLinks(bool) metoda

Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Zapisz **bool**. Domyślna wartość to **false**.

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_SkipJavaScriptLinks(bool value)=0
```

## Uwagi

Gdy ta właściwość jest ustawiona na **true**, hiperłącza z wywołaniami JavaScript będą pomijane podczas zapisywania.

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