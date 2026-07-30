---
title: set_DisableFontLigatures()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nastavuje hodnotu, která určuje, zda je text vykreslován bez použití ligatur. Když je nastavena na true, ligatury budou v renderovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na false.
type: docs
weight: 144
url: /cs/aspose.slides.export/ihtml5options/set_disablefontligatures/
---
## IHtml5Options::set_DisableFontLigatures(bool) metoda


Nastavuje hodnotu, která určuje, zda je text vykreslován bez použití ligatur. Když je nastavena na **true**, ligatury budou v renderovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na **false**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_DisableFontLigatures(bool value)=0
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Zakázat ligatury při vykreslování textu

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Viz také

* Třída [IHtml5Options](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)