---
title: set_DisableFontLigatures()
second_title: Aspose.Slides pro C++ API Reference
description: Nastavuje hodnotu určující, zda je text vykreslován bez použití ligatur. Když je nastaven na true, ligatury budou v renderovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na false.
type: docs
weight: 196
url: /cs/aspose.slides.export/ihtmloptions/set_disablefontligatures/
---
## IHtmlOptions::set_DisableFontLigatures(bool) metoda

Nastaví hodnotu určující, zda je text vykreslován bez použití ligatur. Když je nastavena na **true**, ligatury budou v renderovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na **false**.

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_DisableFontLigatures(bool value)=0
```

## Poznámky

Příklad:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Zakázat ligatury při vykreslování textu

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Viz také

* Třída [IHtmlOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)