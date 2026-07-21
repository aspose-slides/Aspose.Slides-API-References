---
title: GetFontBytes()
second_title: Справка API Aspose.Slides для C++
description: Получает массив байтов, представляющий данные шрифта для указанного стиля шрифта и данных шрифта.
type: docs
weight: 131
url: /ru/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) метод


Получает массив байтов, представляющий данные шрифта для указанного стиля шрифта и данных шрифта.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Объект данных шрифта, содержащий информацию о шрифте [IFontData](../../ifontdata/). |
| fontStyle | [FontStyleType](../../fontstyletype/) | Стиль шрифта, для которого необходимо получить данные [FontStyleType](../../fontstyletype/). |

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

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)