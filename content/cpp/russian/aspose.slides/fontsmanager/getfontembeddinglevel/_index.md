---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides для C++ справочник API
description: Определяет уровень внедрения шрифта из указанного массива байтов и имени шрифта.
type: docs
weight: 144
url: /ru/aspose.slides/fontsmanager/getfontembeddinglevel/
---
## FontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) метод

Определяет уровень внедрения шрифта из указанного массива байтов и имени шрифта.

```cpp
Aspose::Slides::EmbeddingLevel Aspose::Slides::FontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив байтов, содержащий данные шрифта. |
| fontName | [System::String](../../../system/string/) | Имя шрифта. |

### Возвращаемое значение

Уровень внедрения указанного шрифта.

## Примечания

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determine the embedding level of the font
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## См. также

* Перечисление [EmbeddingLevel](../../embeddinglevel/)
* Типовое определение [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [FontsManager](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)