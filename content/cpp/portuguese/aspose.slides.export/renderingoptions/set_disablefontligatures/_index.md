---
title: set_DisableFontLigatures()
second_title: Referência da API Aspose.Slides para C++
description: Define um valor que indica se o texto é renderizado sem usar ligaduras. Quando definido como true, as ligaduras serão desativadas na saída renderizada. Por padrão, esta propriedade está definida como false.
type: docs
weight: 53
url: /pt/aspose.slides.export/renderingoptions/set_disablefontligatures/
---
## RenderingOptions::set_DisableFontLigatures(bool) método

Define um valor que indica se o texto é renderizado sem usar ligaduras. Quando definido como **true**, as ligaduras serão desativadas na saída renderizada. Por padrão, esta propriedade está definida como **false**.

```cpp
void Aspose::Slides::Export::RenderingOptions::set_DisableFontLigatures(bool value) override
```

## Observações

Exemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Desativar ligaduras na renderização de texto

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Veja Também

* Classe [RenderingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)