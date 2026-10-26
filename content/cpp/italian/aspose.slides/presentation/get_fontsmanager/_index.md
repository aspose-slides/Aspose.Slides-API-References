---
title: get_FontsManager()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il gestore dei font. Solo lettura IFontsManager.
type: docs
weight: 157
url: /it/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() metodo


Restituisce il gestore dei font. Solo lettura [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## Osservazioni


Il seguente esempio mostra come aggiungere font incorporati a PowerPoint [Presentation](../).
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

// Save the presentation
presentation->Save(u"AddEmbeddedFont_out.pptx", SaveFormat::Pptx);
```




## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontsManager](../../ifontsmanager/)
* Classe [Presentation](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)