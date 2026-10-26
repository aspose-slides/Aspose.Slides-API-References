---
title: GetFontBytes()
second_title: Riferimento API di Aspose.Slides per C++
description: Recupera l'array di byte che rappresenta i dati del font per uno stile di font e dati del font specificati.
type: docs
weight: 131
url: /it/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) method

Recupera l'array di byte che rappresenta i dati del font per lo stile di font e i dati del font specificati.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | L'oggetto dei dati del font contenente le informazioni sul font [IFontData](../../ifontdata/). |
| fontStyle | [FontStyleType](../../fontstyletype/) | Lo stile del font per il quale i dati devono essere recuperati [FontStyleType](../../fontstyletype/). |

### Valore di ritorno

Un array di byte contenente i dati del font per lo stile di font specificato. Se i dati del font o lo stile non sono trovati, restituisce null.

## Note

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## Vedi anche

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)