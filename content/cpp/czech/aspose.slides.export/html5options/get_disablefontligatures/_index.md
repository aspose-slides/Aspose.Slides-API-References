---
title: get_DisableFontLigatures()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací hodnotu, která určuje, zda je text vykreslován bez použití ligatur. Když je nastaveno na true, budou ligatury ve výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na false.
type: docs
weight: 131
url: /cs/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() metoda

Vrací hodnotu, která určuje, zda je text vykreslován bez použití ligatur. Když je nastavena na **true**, ligatury budou ve výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na **false**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
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