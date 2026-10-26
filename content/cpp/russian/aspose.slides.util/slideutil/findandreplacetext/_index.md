---
title: FindAndReplaceText()
second_title: Aspose.Slides для C++ справочник API
description: Находит и заменяет текст в презентации с заданным форматом
type: docs
weight: 40
url: /ru/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) метод

Находит и заменяет текст в презентации с заданным форматом

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Отсканированная презентация. |
| withMasters | **bool** | Определяет, следует ли сканировать слайды-мастера. |
| find | [System::String](../../../system/string/) | Строковое значение для поиска. |
| replace | [System::String](../../../system/string/) | Строковое значение для замены. |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | Формат для замены части текста. Если null, будет использован формат первого символа найденной строки |

## Замечания


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto format = System::MakeObject<PortionFormat>();
format->set_FontHeight(24.0f);
format->set_FontItalic(NullableBool::True);
auto fillFormat = format->get_FillFormat();
fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());

SlideUtil::FindAndReplaceText(pres, true, u"[this block] ", u"my text ", format);
pres->Save(u"replaced", SaveFormat::Pptx);
```


## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IPresentation](../../../aspose.slides/ipresentation/)
* Класс [String](../../../system/string/)
* Класс [PortionFormat](../../../aspose.slides/portionformat/)
* Класс [SlideUtil](../)
* Пространство имён [Aspose::Slides::Util](../../)
* Библиотека [Aspose.Slides](../../../)