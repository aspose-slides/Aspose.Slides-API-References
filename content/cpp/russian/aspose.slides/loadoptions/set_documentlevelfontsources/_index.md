---
title: set_DocumentLevelFontSources()
second_title: Aspose.Slides для справочника API C++
description: Указывает источники внешних шрифтов, которые будут использоваться в презентации. Эти шрифты доступны презентации на протяжении её жизненного цикла и не разделяются с другими презентациями
type: docs
weight: 222
url: /ru/aspose.slides/loadoptions/set_documentlevelfontsources/
---
## LoadOptions::set_DocumentLevelFontSources(System::SharedPtr\<IFontSources\>) method


Указывает источники внешних шрифтов, которые будут использоваться в презентации. Эти шрифты доступны презентации на протяжении её жизненного цикла и не разделяются с другими презентациями

```cpp
void Aspose::Slides::LoadOptions::set_DocumentLevelFontSources(System::SharedPtr<IFontSources> value) override
```

## Remarks


Следующий пример показывает, как указать пользовательские шрифты, используемые в PowerPoint [Presentation](../../presentation/). 
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// работа с презентацией
// CustomFont1, CustomFont2, а также шрифты из папок assets\fonts и global\fonts и их подпапок доступны презентации
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IFontSources](../../ifontsources/)
* Класс [LoadOptions](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)