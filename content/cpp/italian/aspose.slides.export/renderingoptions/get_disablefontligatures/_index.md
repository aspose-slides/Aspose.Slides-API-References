---
title: get_DisableFontLigatures()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un valore che indica se il testo viene renderizzato senza utilizzare legature. Quando impostato su true, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su false.
type: docs
weight: 40
url: /it/aspose.slides.export/renderingoptions/get_disablefontligatures/
---
## RenderingOptions::get_DisableFontLigatures() metodo

Restituisce un valore che indica se il testo viene renderizzato senza utilizzare le legature. Quando impostato su **true**, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su **false**.

```cpp
bool Aspose::Slides::Export::RenderingOptions::get_DisableFontLigatures() override
```
## Osservazioni


Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Disabilita le legature nella resa del testo

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Vedi anche

* Classe [RenderingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)