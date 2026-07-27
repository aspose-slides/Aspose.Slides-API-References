---
title: set_DisableFontLigatures()
second_title: Referência da API Aspose.Slides para C++
description: Define um valor que indica se o texto é renderizado sem usar ligaturas. Quando definido como true, as ligaturas serão desativadas na saída renderizada. Por padrão, esta propriedade é definida como false.
type: docs
weight: 53
url: /pt/aspose.slides.export/irenderingoptions/set_disablefontligatures/
---
## IRenderingOptions::set_DisableFontLigatures(bool) método


Define um valor que indica se o texto é renderizado sem usar ligaturas. Quando definido como **true**, as ligaturas serão desativadas na saída renderizada. Por padrão, esta propriedade é definida como **false**.

```cpp
virtual void Aspose::Slides::Export::IRenderingOptions::set_DisableFontLigatures(bool value)=0
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Desativar ligaturas na renderização de texto

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Ver também

* Classe [IRenderingOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)