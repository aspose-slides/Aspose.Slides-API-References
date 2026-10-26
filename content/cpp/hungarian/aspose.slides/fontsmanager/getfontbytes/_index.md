---
title: GetFontBytes()
second_title: Aspose.Slides C++ API referencia
description: A megadott betűstílushoz és betűadatokhoz tartozó betűadatot reprezentáló bájt tömböt ad vissza.
type: docs
weight: 131
url: /hu/aspose.slides/fontsmanager/getfontbytes/
---
## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, Aspose::Slides::FontStyleType) method

A megadott betűstílus és betűadatokhoz tartozó betűadatot reprezentáló bájt tömböt adja vissza.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, Aspose::Slides::FontStyleType fontStyle) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | A betűadat-objektum, amely tartalmazza a(z) [IFontData](../../ifontdata/) betűtípusról szóló információkat. |
| fontStyle | [Aspose::Slides::FontStyleType](../../fontstyletype/) | A betűtípus stílusa, amelyhez a adatokat le kell kérni [FontStyleType](../../fontstyletype/). |

### Visszatérési érték

Egy bájt tömb, amely a megadott betűstílushoz tartozó betűadatokat tartalmazza. Ha a betűadat vagy a stílus nem található, null értékkel tér vissza.

## Megjegyzések

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## Lásd még

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)