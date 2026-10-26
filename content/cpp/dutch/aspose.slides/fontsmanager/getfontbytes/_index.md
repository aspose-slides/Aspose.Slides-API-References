---
title: GetFontBytes()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt het byte-array op dat de lettertype-gegevens vertegenwoordigt voor een opgegeven lettertype-stijl en lettertype-gegevens.
type: docs
weight: 131
url: /nl/aspose.slides/fontsmanager/getfontbytes/
---
## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, Aspose::Slides::FontStyleType) methode

Haalt het byte-array op dat de lettertype-gegevens vertegenwoordigt voor een opgegeven lettertype-stijl en lettertype-gegevens.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, Aspose::Slides::FontStyleType fontStyle) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | Het lettertype-gegevensobject dat de informatie over het lettertype [IFontData](../../ifontdata/) bevat. |
| fontStyle | [Aspose::Slides::FontStyleType](../../fontstyletype/) | De stijl van het lettertype waarvoor de gegevens moeten worden opgehaald [FontStyleType](../../fontstyletype/). |

### Retourwaarde

Een byte-array dat de lettertype-gegevens bevat voor de opgegeven lettertype-stijl. Als de lettertype-gegevens of stijl niet worden gevonden, wordt null geretourneerd.

## Opmerkingen




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## Zie ook

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontData](../../ifontdata/)
* Klasse [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)