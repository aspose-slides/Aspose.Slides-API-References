---
title: GetFontBytes()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft das Byte-Array ab, das die Font-Daten für einen angegebenen Schriftstil und Font-Daten darstellt.
type: docs
weight: 131
url: /de/aspose.slides/fontsmanager/getfontbytes/
---
## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, Aspose::Slides::FontStyleType) Methode

Ruft das Byte-Array ab, das die Font-Daten für einen angegebenen Schriftstil und Font-Daten darstellt.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, Aspose::Slides::FontStyleType fontStyle) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | Das Font-Datenobjekt, das die Informationen zur Schrift [IFontData](../../ifontdata/) enthält. |
| fontStyle | [Aspose::Slides::FontStyleType](../../fontstyletype/) | Der Stil der Schrift, für die die Daten abgerufen werden sollen [FontStyleType](../../fontstyletype/). |

### Rückgabewert

Ein Byte-Array, das die Font-Daten für den angegebenen Schriftstil enthält. Wenn die Font-Daten oder der Stil nicht gefunden werden, wird null zurückgegeben.

## Bemerkungen

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
* Klasse [IFontData](../../ifontdata/)
* Klasse [FontsManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)