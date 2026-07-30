---
title: set_DisableFontLigatures()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Nastavuje hodnotu, která určuje, zda je text vykreslován bez použití ligatur. Když je nastavena na true, ligatury budou v renderovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na false.
type: docs
weight: 105
url: /cs/aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) metoda

Nastavuje hodnotu určující, zda je text vykreslován bez použití ligatur. Když je nastavena na **true**, ligatury budou v renderovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na **false**.

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
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