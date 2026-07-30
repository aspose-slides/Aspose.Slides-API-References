---
title: set_DisableFontLigatures()
second_title: Aspose.Slides pro C++ API Reference
description: Nastavuje hodnotu určující, zda je text vykreslován bez použití ligatur. Když je nastaveno na true, ligatury budou ve výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na false.
type: docs
weight: 53
url: /cs/aspose.slides.export/renderingoptions/set_disablefontligatures/
---
## RenderingOptions::set_DisableFontLigatures(bool) metoda


Nastavuje hodnotu určující, zda je text vykreslován bez použití ligatur. Když je nastaveno na **true**, ligatury budou ve výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na **false**.

```cpp
void Aspose::Slides::Export::RenderingOptions::set_DisableFontLigatures(bool value) override
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

* Třída [RenderingOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)