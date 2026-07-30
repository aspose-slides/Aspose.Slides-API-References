---
title: set_DisableFontLigatures()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta un valore che indica se il testo viene visualizzato senza utilizzare le legature. Quando è impostato su true, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su false.
type: docs
weight: 53
url: /it/aspose.slides.export/renderingoptions/set_disablefontligatures/
---
## RenderingOptions::set_DisableFontLigatures(bool) metodo

Imposta un valore che indica se il testo viene visualizzato senza utilizzare le legature. Quando è impostato su **true**, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su **false**.

```cpp
void Aspose::Slides::Export::RenderingOptions::set_DisableFontLigatures(bool value) override
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
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)