---
title: set_DisableFontLigatures()
second_title: Aspose.Slides pro C++ API Reference
description: Nastaví hodnotu indikující, zda je text vykreslován bez použití ligatur. Pokud je nastaveno na true, budou ligatury v renderovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na false.
type: docs
weight: 144
url: /cs/aspose.slides.export/html5options/set_disablefontligatures/
---
## Html5Options::set_DisableFontLigatures(bool) metoda


Nastaví hodnotu indikující, zda je text vykreslován bez použití ligatur. Pokud je nastaveno na **true**, ligatury budou v renderovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na **false**.

```cpp
void Aspose::Slides::Export::Html5Options::set_DisableFontLigatures(bool value) override
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

* Třída [Html5Options](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)