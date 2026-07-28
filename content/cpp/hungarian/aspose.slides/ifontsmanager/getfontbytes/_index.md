---
title: GetFontBytes()
second_title: Aspose.Slides C++ API-referencia
description: Visszaadja a megadott betűstílus és betűadatok fontadatait tartalmazó byte tömböt.
type: docs
weight: 131
url: /hu/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) metódus

Visszaadja azt a byte tömböt, amely a megadott betűstílus és betűadatok font adatait tartalmazza.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | A betűtípus adat objektum, amely a [IFontData](../../ifontdata/) betűtípusról tartalmaz információkat. |
| fontStyle | [FontStyleType](../../fontstyletype/) | A betűtípus stílusa, amelynek az adatát le kell kérni [FontStyleType](../../fontstyletype/). |

### Visszatérési érték

Egy byte tömb, amely a megadott betűstílus font adatait tartalmazza. Ha a betűtípus adat vagy a stílus nem található, null értékkel tér vissza.

## Megjegyzés

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
* Osztály [IFontData](../../ifontdata/)
* Osztály [IFontsManager](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)