---
title: get_DisableFontLigatures()
second_title: Aspose.Slides pro C++ referenční dokumentaci API
description: Vrací hodnotu, která udává, zda je text vykreslován bez použití ligatur. Pokud je nastaveno na true, ligatury budou vygenerovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na false.
type: docs
weight: 40
url: /cs/aspose.slides.export/irenderingoptions/get_disablefontligatures/
---
## IRenderingOptions::get_DisableFontLigatures() metoda


Vrací hodnotu, která udává, zda je text vykreslován bez použití ligatur. Pokud je nastaveno na **true**, ligatury budou vygenerovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na **false**.

```cpp
virtual bool Aspose::Slides::Export::IRenderingOptions::get_DisableFontLigatures()=0
```

## Poznámky


Příklad:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Zakázat ligatury při vykreslování textu

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Viz také

* Třída [IRenderingOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)