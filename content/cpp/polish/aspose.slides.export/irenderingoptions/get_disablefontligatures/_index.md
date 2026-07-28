---
title: get_DisableFontLigatures()
second_title: Aspose.Slides dla C++ – referencja API
description: Zwraca wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na true, ligatury będą wyłączone w renderowanym wyjściu. Domyślnie ta właściwość ma wartość false.
type: docs
weight: 40
url: /pl/aspose.slides.export/irenderingoptions/get_disablefontligatures/
---
## IRenderingOptions::get_DisableFontLigatures() metoda

Zwraca wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na **true**, ligatury będą wyłączone w renderowanym wyjściu. Domyślnie ta właściwość ma wartość **false**.

```cpp
virtual bool Aspose::Slides::Export::IRenderingOptions::get_DisableFontLigatures()=0
```

## Uwagi

Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Wyłącz ligatury podczas renderowania tekstu

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Zobacz także

* Klasa [IRenderingOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)