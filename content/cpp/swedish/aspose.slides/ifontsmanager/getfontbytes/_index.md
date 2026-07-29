---
title: GetFontBytes()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar bytearrayen som representerar teckensnittsdata för en specificerad teckensnittsstil och teckensnittsdata.
type: docs
weight: 131
url: /sv/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) metod


Hämtar bytearrayen som representerar teckensnittsdata för en angiven teckensnittsstil och teckensnittsdata.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Teckensnittsdataobjektet som innehåller informationen om teckensnittet [IFontData](../../ifontdata/). |
| fontStyle | [FontStyleType](../../fontstyletype/) | Stilen på teckensnittet för vilket data ska hämtas [FontStyleType](../../fontstyletype/). |

### Returvärde

En bytearray som innehåller teckensnittsdata för den specificerade teckensnittsstilen. Om teckensnittsdata eller stil inte hittas, returneras null.
## Anmärkningar




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## Se också

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)