---
title: get_DefaultRegularFont()
second_title: Aspose.Slides для C++ справки API
description: "Возвращает обычный шрифт, используемый в случае, если исходный шрифт не найден. Читайте System::String."
type: docs
weight: 27
url: /ru/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() метод


Возвращает обычный шрифт, используемый в случае, если исходный шрифт не найден. Читайте [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## Примечания


Следующий пример показывает, как установить шрифты по умолчанию для рендеринга PowerPoint [Presentation](../../presentation/). 
```cpp
// Используйте параметры загрузки, чтобы задать шрифты по умолчанию для обычных и азиатских шрифтов
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Загрузить презентацию
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Создать миниатюру слайда
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Создать PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Создать XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [LoadOptions](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)