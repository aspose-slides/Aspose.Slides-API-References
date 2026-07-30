---
title: get_DisableFontLigatures()
second_title: Aspose.Slides pro C++ API Reference
description: Získá hodnotu, která určuje, zda je text vykreslován bez použití ligatur. Když je nastaveno na true, ligatury budou v renderovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na false.
type: docs
weight: 92
url: /cs/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() metoda


Získá hodnotu, která určuje, zda je text vykreslován bez použití ligatur. Když je nastaveno na **true**, ligatury budou v renderovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na **false**.

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
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

* Třída [HtmlOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)