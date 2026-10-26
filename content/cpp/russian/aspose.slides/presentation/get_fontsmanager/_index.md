---
title: get_FontsManager()
second_title: Aspose.Slides для C++ API справка
description: Возвращает менеджер шрифтов. Только для чтения IFontsManager.
type: docs
weight: 157
url: /ru/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() метод


Возвращает менеджер шрифтов. Только для чтения [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## Примечания


Следующий пример показывает, как добавить встроенные шрифты в PowerPoint [Presentation](../). 
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




## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IFontsManager](../../ifontsmanager/)
* Класс [Presentation](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)