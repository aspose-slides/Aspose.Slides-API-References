---
title: get_DisableFontLigatures()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Zwraca wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na true, ligatury zostaną wyłączone w renderowanym wyjściu. Domyślnie ta właściwość jest ustawiona na false.
type: docs
weight: 40
url: /pl/aspose.slides.export/renderingoptions/get_disablefontligatures/
---
## RenderingOptions::get_DisableFontLigatures() metoda


Zwraca wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na **true**, ligatury zostaną wyłączone w renderowanym wyjściu. Domyślnie ta właściwość jest ustawiona na **false**.

```cpp
bool Aspose::Slides::Export::RenderingOptions::get_DisableFontLigatures() override
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Wyłącz ligatury w renderowaniu tekstu

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Zobacz także

* Klasa [RenderingOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)