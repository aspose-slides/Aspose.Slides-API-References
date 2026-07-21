---
title: GetFontName()
second_title: Aspose.Slides для C++ справка API
description: Возвращает имя шрифта, заменяя ссылку на тему фактическим используемым шрифтом.
type: docs
weight: 27
url: /ru/aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) метод


Возвращает имя шрифта, заменяя ссылку на тему фактическим используемым шрифтом.

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/) из которой следует взять имя шрифта темы. Ответственность за предоставление правильного значения лежит на вызывающем. См. [IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/) |

### Возвращаемое значение

Имя шрифта.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* Класс [FontData](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)