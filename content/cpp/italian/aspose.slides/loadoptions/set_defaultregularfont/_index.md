---
title: set_DefaultRegularFont()
second_title: Riferimento API Aspose.Slides per C++
description: "Imposta il carattere Regular utilizzato nel caso in cui il carattere sorgente non sia trovato. Scrivi System::String."
type: docs
weight: 40
url: /it/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) metodo


Imposta il carattere Regular utilizzato nel caso in cui il carattere sorgente non sia trovato. Scrivi [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## Osservazioni


Il seguente esempio mostra come impostare i caratteri predefiniti per il rendering di PowerPoint [Presentation](../../presentation/). 
```cpp
// Utilizza le opzioni di caricamento per definire i caratteri regular e asian predefiniti
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Carica la presentazione
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Genera la miniatura della diapositiva
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
* Libreria [Aspose.Slides](../../../)