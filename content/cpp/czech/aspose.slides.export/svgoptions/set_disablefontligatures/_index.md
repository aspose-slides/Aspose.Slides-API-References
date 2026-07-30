---
title: set_DisableFontLigatures()
second_title: Aspose.Slides pro C++ API Reference
description: Nastavuje hodnotu určující, zda je text vykreslován bez použití ligatur. Pokud je nastaveno na true, ligatury budou vygenerovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na false.
type: docs
weight: 339
url: /cs/aspose.slides.export/svgoptions/set_disablefontligatures/
---
## SVGOptions::set_DisableFontLigatures(bool) metoda


Nastavuje hodnotu určující, zda je text vykreslován bez použití ligatur. Pokud je nastaveno na **true**, ligatury budou vygenerovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na **false**.

```cpp
void Aspose::Slides::Export::SVGOptions::set_DisableFontLigatures(bool value) override
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

* Třída [SVGOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)