---
title: GetFontBytes()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft das Byte-Array ab, das die Schriftartdaten für einen angegebenen Schriftstil und die zugehörigen Font-Daten darstellt.
type: docs
weight: 131
url: /de/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) Methode

Ruft das Byte-Array ab, das die Font-Daten für einen angegebenen Schriftstil und Font-Daten darstellt.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Das Font-Datenobjekt, das die Informationen über die Schrift [IFontData](../../ifontdata/) enthält. |
| fontStyle | [FontStyleType](../../fontstyletype/) | Der Stil der Schrift, für die die Daten abgerufen werden sollen [FontStyleType](../../fontstyletype/). |

### Rückgabewert

Ein Byte-Array, das die Font-Daten für den angegebenen Schriftstil enthält. Wenn die Font-Daten oder der Stil nicht gefunden werden, wird null zurückgegeben.

## Anmerkungen

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## Siehe auch

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)