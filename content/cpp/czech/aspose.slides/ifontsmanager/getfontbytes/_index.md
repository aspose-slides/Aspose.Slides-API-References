---
title: GetFontBytes()
second_title: Aspose.Slides pro C++ - reference API
description: Vrací pole bajtů představující data fontu pro zadaný styl fontu a data fontu.
type: docs
weight: 131
url: /cs/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) metoda


Vrací pole bajtů představující data fontu pro specifikovaný styl fontu a data fontu.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Objekt dat fontu obsahující informace o fontu [IFontData](../../ifontdata/). |
| fontStyle | [FontStyleType](../../fontstyletype/) | Styl fontu, pro který mají být data získány [FontStyleType](../../fontstyletype/). |

### Návratová hodnota

Pole bajtů obsahující data fontu pro zadaný styl fontu. Pokud data fontu nebo styl nejsou nalezeny, vrací null.
## Poznámky




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## Viz také

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)