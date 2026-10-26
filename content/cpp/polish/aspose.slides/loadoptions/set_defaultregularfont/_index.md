---
title: set_DefaultRegularFont()
second_title: Aspose.Slides dla C++ odwołanie API
description: "Ustawia czcionkę Regular używaną w przypadku, gdy nie zostanie znaleziona czcionka źródłowa. Zapisz System::String."
type: docs
weight: 40
url: /pl/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) metoda

Ustawia czcionkę Regular, używaną w przypadku, gdy nie zostanie znaleziona czcionka źródłowa. Zapisz [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## Uwagi

Poniższy przykład pokazuje, jak ustawić czcionki domyślne dla renderowania PowerPoint [Presentation](../../presentation/).
```cpp
// Użyj opcji ładowania, aby zdefiniować domyślne czcionki regular i azjatyckie
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Załaduj prezentację
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Wygeneruj miniaturę slajdu
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