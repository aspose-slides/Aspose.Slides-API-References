---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει το επίπεδο ενσωμάτωσης μιας γραμματοσειράς από τον δεδομένο πίνακα byte και το όνομα της γραμματοσειράς.
type: docs
weight: 144
url: /el/aspose.slides/fontsmanager/getfontembeddinglevel/
---
## FontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) μέθοδος


Καθορίζει το επίπεδο ενσωμάτωσης μιας γραμματοσειράς από τον δεδομένο πίνακα byte και το όνομα της γραμματοσειράς.

```cpp
Aspose::Slides::EmbeddingLevel Aspose::Slides::FontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ο πίνακας byte που περιέχει τα δεδομένα της γραμματοσειράς. |
| fontName | [System::String](../../../system/string/) | Το όνομα της γραμματοσειράς. |

### Τιμή Επιστροφής

Το επίπεδο ενσωμάτωσης της συγκεκριμένης γραμματοσειράς.
## Παρατηρήσεις




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determine the embedding level of the font
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## Δείτε επίσης

* Απαρίθμηση [EmbeddingLevel](../../embeddinglevel/)
* Τύπος [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [FontsManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)