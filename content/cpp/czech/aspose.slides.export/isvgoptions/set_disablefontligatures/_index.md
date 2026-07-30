---
title: set_DisableFontLigatures()
second_title: Aspose.Slides pro C++ – reference API
description: Nastaví hodnotu, která určuje, zda je text vykreslován bez použití ligatur. Když je nastaven na true, ligatury budou v renderovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na false.
type: docs
weight: 339
url: /cs/aspose.slides.export/isvgoptions/set_disablefontligatures/
---
## ISSVGOptions::set_DisableFontLigatures(bool) metoda


Nastaví hodnotu, která určuje, zda je text vykreslován bez použití ligatur. Když je nastavena na **true**, ligatury budou v renderovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na **false**.

```cpp
virtual void Aspose::Slides::Export::ISVGOptions::set_DisableFontLigatures(bool value)=0
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Zakázat ligatury při vykreslování textu

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Viz také

* Třída [ISVGOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)