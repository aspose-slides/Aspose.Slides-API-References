---
title: get_DefaultRegularFont()
second_title: Aspose.Slides dla C++ - odniesienie API
description: "Zwraca czcionkę Regular używaną w przypadku, gdy nie znaleziono czcionki źródłowej. Przeczytaj System::String."
type: docs
weight: 27
url: /pl/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() metoda

Zwraca czcionkę Regular używaną w przypadku, gdy nie znaleziono czcionki źródłowej. Przeczytaj [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## Uwagi

Poniższy przykład pokazuje, jak ustawić domyślne czcionki dla renderowania PowerPointa [Presentation](../../presentation/).
```cpp
// Użyj opcji ładowania, aby określić domyślne czcionki regularne i azjatyckie
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Wczytaj prezentację
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Wygeneruj miniaturkę slajdu
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Wygeneruj PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Wygeneruj XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [LoadOptions](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)