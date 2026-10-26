---
title: GetFontBytes()
second_title: Aspose.Slides для C++: справка API
description: Возвращает массив байтов, представляющий данные шрифта для указанного стиля шрифта и данных шрифта.
type: docs
weight: 131
url: /ru/aspose.slides/fontsmanager/getfontbytes/
---
## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, Aspose::Slides::FontStyleType) метод

Возвращает массив байтов, представляющий данные шрифта для указанного стиля шрифта и данных шрифта.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, Aspose::Slides::FontStyleType fontStyle) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | Объект данных шрифта, содержащий информацию о шрифте [IFontData](../../ifontdata/). |
| fontStyle | [Aspose::Slides::FontStyleType](../../fontstyletype/) | Стиль шрифта, для которого необходимо получить данные [FontStyleType](../../fontstyletype/). |

### Возвращаемое значение

Массив байтов, содержащий данные шрифта для указанного стиля шрифта. Если данные шрифта или стиль не найдены, возвращает null.

## Примечания

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## См. также

* Перечисление [FontStyleType](../../fontstyletype/)
* Определение типа [ArrayPtr](../../../system/arrayptr/)
* Определение типа [SharedPtr](../../../system/sharedptr/)
* Класс [IFontData](../../ifontdata/)
* Класс [FontsManager](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)