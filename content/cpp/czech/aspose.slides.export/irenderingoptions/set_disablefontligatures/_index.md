---
title: set_DisableFontLigatures()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nastavuje hodnotu určující, zda je text vykreslován bez použití ligatur. Když je nastaveno na true, ligatury budou ve výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na false.
type: docs
weight: 53
url: /cs/aspose.slides.export/irenderingoptions/set_disablefontligatures/
---
## IRenderingOptions::set_DisableFontLigatures(bool) metoda

Nastavuje hodnotu určující, zda je text vykreslován bez použití ligatur. Když je nastaveno na **true**, ligatury budou ve výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na **false**.

```cpp
virtual void Aspose::Slides::Export::IRenderingOptions::set_DisableFontLigatures(bool value)=0
```

## Poznámky


Example: 
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