---
title: GetFontBytes()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar bytearrayen som representerar fontdata för en specificerad fontstil och fontdata.
type: docs
weight: 131
url: /sv/aspose.slides/fontsmanager/getfontbytes/
---
## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, Aspose::Slides::FontStyleType) metod

Hämtar bytearrayen som representerar fontdata för en specificerad fontstil och fontdata.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, Aspose::Slides::FontStyleType fontStyle) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | Objektet för fontdata som innehåller informationen om teckensnittet [IFontData](../../ifontdata/). |
| fontStyle | [Aspose::Slides::FontStyleType](../../fontstyletype/) | Stilen för teckensnittet som data ska hämtas för [FontStyleType](../../fontstyletype/). |

### Returvärde

En bytearray som innehåller fontdata för den specificerade teckensnittsstilen. Om fontdata eller stil inte hittas, returneras null.

## Anmärkningar

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Hämta alla teckensnitt som används i presentationen
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Hämta bytearrayen som representerar den reguljära stilen för det första teckensnittet i presentationen
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## Se även

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IFontData](../../ifontdata/)
* Klass [FontsManager](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)