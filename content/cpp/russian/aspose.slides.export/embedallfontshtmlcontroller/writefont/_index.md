---
title: WriteFont()
second_title: Справочник API Aspose.Slides для C++
description: Записывает данные в виде base64 непосредственно в HTML-документ
type: docs
weight: 105
url: /ru/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) метод

Записывает данные в виде base64 напрямую в HTML-документ

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | HTML-генератор |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Шрифт для сериализации |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Заменённый шрифт (если произошла подстановка шрифта), иначе null |
| fontStyle | [System::String](../../../system/string/) | Стиль шрифта |
| fontWeight | [System::String](../../../system/string/) | Толщина шрифта |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Данные шрифта |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [IHtmlGenerator](../../ihtmlgenerator/)
* Класс [IFontData](../../../aspose.slides/ifontdata/)
* Класс [String](../../../system/string/)
* Класс [EmbedAllFontsHtmlController](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)