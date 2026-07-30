---
title: get_DefaultRegularFont()
second_title: Riferimento API di Aspose.Slides per C++
description: "Restituisce il font Regular usato nel caso in cui il font di origine non sia trovato. Leggi System::String."
type: docs
weight: 27
url: /it/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() metodo


Restituisce il font Regular usato nel caso in cui il font di origine non sia trovato. Leggi [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## Osservazioni


Il seguente esempio mostra come impostare i font predefiniti per il rendering di PowerPoint [Presentation](../../presentation/). 
```cpp
// Utilizza le opzioni di caricamento per definire i font regular e asiatici predefiniti
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Carica la presentazione
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Genera l'anteprima della diapositiva
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Genera PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Genera XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [LoadOptions](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)