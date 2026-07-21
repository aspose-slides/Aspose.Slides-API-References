---
title: get_DocumentLevelFontSources()
second_title: Справочник API Aspose.Slides для C++
description: Указывает источники внешних шрифтов, которые будут использоваться в презентации. Эти шрифты доступны презентации на протяжении всей её жизни и не совместно используются с другими презентациями
type: docs
weight: 209
url: /ru/aspose.slides/loadoptions/get_documentlevelfontsources/
---
## LoadOptions::get_DocumentLevelFontSources() метод

Указывает источники внешних шрифтов, которые будут использоваться в презентации. Эти шрифты доступны презентации на протяжении всего её срока жизни и не совместно используются с другими презентациями

```cpp
System::SharedPtr<IFontSources> Aspose::Slides::LoadOptions::get_DocumentLevelFontSources() override
```

## Примечания

Следующий пример показывает, как указать пользовательские шрифты, используемые в PowerPoint [Presentation](../../presentation/). 
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// работа с презентацией
// CustomFont1, CustomFont2, а также шрифты из папок assets\fonts и global\fonts и их подпапок доступны в презентации
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IFontSources](../../ifontsources/)
* Класс [LoadOptions](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)