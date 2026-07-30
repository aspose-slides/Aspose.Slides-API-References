---
title: GetFontBytes()
second_title: Riferimento API Aspose.Slides per C++
description: Recupera l'array di byte che rappresenta i dati del font per uno stile di font specificato e i dati del font.
type: docs
weight: 131
url: /it/aspose.slides/fontsmanager/getfontbytes/
---
## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, Aspose::Slides::FontStyleType) metodo

Recupera l'array di byte che rappresenta i dati del font per uno stile di font specificato e i dati del font.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, Aspose::Slides::FontStyleType fontStyle) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | L'oggetto dati del font che contiene le informazioni sul font [IFontData](../../ifontdata/). |
| fontStyle | [Aspose::Slides::FontStyleType](../../fontstyletype/) | Lo stile del font per il quale i dati devono essere recuperati [FontStyleType](../../fontstyletype/). |

### Valore di ritorno

Un array di byte contenente i dati del font per lo stile di font specificato. Se i dati del font o lo stile non vengono trovati, ritorna null.

## Osservazioni




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
* Classe [IFontData](../../ifontdata/)
* Classe [FontsManager](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)