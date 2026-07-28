---
title: GetFontBytes()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Pobiera tablicę bajtów reprezentującą dane czcionki dla określonego stylu czcionki i danych czcionki.
type: docs
weight: 131
url: /pl/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) method

Pobiera tablicę bajtów reprezentującą dane czcionki dla określonego stylu czcionki i danych czcionki.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Obiekt danych czcionki zawierający informacje o czcionce [IFontData](../../ifontdata/). |
| fontStyle | [FontStyleType](../../fontstyletype/) | Styl czcionki, dla którego mają zostać pobrane dane [FontStyleType](../../fontstyletype/). |

### Wartość zwracana

Tablica bajtów zawierająca dane czcionki dla określonego stylu czcionki. Jeśli dane czcionki lub styl nie zostaną znalezione, zwraca wartość null.

## Uwagi

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## Zobacz też

* Wyliczenie [FontStyleType](../../fontstyletype/)
* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IFontData](../../ifontdata/)
* Klasa [IFontsManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)