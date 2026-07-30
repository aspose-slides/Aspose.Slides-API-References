---
title: get_DisableFontLigatures()
second_title: Aspose.Slides per C++ Riferimento API
description: Restituisce un valore che indica se il testo viene visualizzato senza utilizzare le legature. Quando impostato su true, le legature saranno disattivate nell'output visualizzato. Per impostazione predefinita, questa proprietà è impostata su false.
type: docs
weight: 40
url: /it/aspose.slides.export/irenderingoptions/get_disablefontligatures/
---
## IRenderingOptions::get_DisableFontLigatures() metodo


Restituisce un valore che indica se il testo viene visualizzato senza utilizzare le legature. Quando impostato su **true**, le legature saranno disattivate nell'output visualizzato. Per impostazione predefinita, questa proprietà è impostata su **false**.

```cpp
virtual bool Aspose::Slides::Export::IRenderingOptions::get_DisableFontLigatures()=0
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

* Classe [IRenderingOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)