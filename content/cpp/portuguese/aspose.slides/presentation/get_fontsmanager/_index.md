---
title: get_FontsManager()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o gerenciador de fontes. Somente leitura IFontsManager.
type: docs
weight: 157
url: /pt/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() método

Retorna o gerenciador de fontes. Somente leitura [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## Observações

O exemplo a seguir demonstra como adicionar fontes incorporadas ao PowerPoint [Presentation](../).
```cpp
auto presentation = System::MakeObject<Presentation>(u"Fonts.pptx");
System::ArrayPtr<System::SharedPtr<IFontData>> allFonts = presentation->get_FontsManager()->GetFonts();
System::ArrayPtr<System::SharedPtr<IFontData>> embeddedFonts = presentation->get_FontsManager()->GetEmbeddedFonts();

for (auto&& font : allFonts)
{
    if (!embeddedFonts->Contains(font))
    {
        presentation->get_FontsManager()->AddEmbeddedFont(font, EmbedFontCharacters::All);
    }
}

// Salvar a apresentação
presentation->Save(u"AddEmbeddedFont_out.pptx", SaveFormat::Pptx);
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontsManager](../../ifontsmanager/)
* Classe [Presentation](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)