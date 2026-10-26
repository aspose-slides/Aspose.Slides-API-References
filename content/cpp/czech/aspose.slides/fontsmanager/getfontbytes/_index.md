---
title: GetFontBytes()
second_title: Aspose.Slides pro C++ - reference API
description: Získá pole bajtů představujících data písma pro specifikovaný styl písma a data písma.
type: docs
weight: 131
url: /cs/aspose.slides/fontsmanager/getfontbytes/
---
## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, Aspose::Slides::FontStyleType) metoda

Načte pole bajtů představující data písma pro zadaný styl písma a data písma.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, Aspose::Slides::FontStyleType fontStyle) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | Objekt dat písma obsahující informace o fontu [IFontData](../../ifontdata/). |
| fontStyle | [Aspose::Slides::FontStyleType](../../fontstyletype/) | Styl písma, pro který mají být data načtena [FontStyleType](../../fontstyletype/). |

### Návratová hodnota

Pole bajtů obsahující data písma pro zadaný styl písma. Pokud data písma nebo styl nejsou nalezeny, vrací null.
## Poznámky

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## Viz také

* Výčet [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IFontData](../../ifontdata/)
* Třída [FontsManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)