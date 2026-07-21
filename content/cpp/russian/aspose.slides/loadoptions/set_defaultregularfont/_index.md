---
title: set_DefaultRegularFont()
second_title: Справочник API Aspose.Slides для C++
description: "Устанавливает обычный шрифт, используемый, если исходный шрифт не найден. Запишите System::String."
type: docs
weight: 40
url: /ru/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) метод

Устанавливает обычный шрифт, используемый, если исходный шрифт не найден. Запишите [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## Примечания

В следующем примере показано, как установить шрифты по умолчанию для рендеринга PowerPoint [Presentation](../../presentation/).
```cpp
// Используйте параметры загрузки, чтобы задать шрифты по умолчанию для обычных и азиатских символов
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Загрузите презентацию
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Создайте миниатюру слайда
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Создайте PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Создайте XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## См. также

* Класс [String](../../../system/string/)
* Класс [LoadOptions](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)