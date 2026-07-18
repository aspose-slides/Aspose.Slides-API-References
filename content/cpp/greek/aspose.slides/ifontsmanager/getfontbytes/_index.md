---
title: GetFontBytes()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ανακτά τον πίνακα byte που αντιπροσωπεύει τα δεδομένα γραμματοσειράς για ένα καθορισμένο στυλ γραμματοσειράς και δεδομένα γραμματοσειράς.
type: docs
weight: 131
url: /el/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) μέθοδος

Ανακτά τον πίνακα byte που αντιπροσωπεύει τα δεδομένα γραμματοσειράς για ένα καθορισμένο στυλ γραμματοσειράς και δεδομένα γραμματοσειράς.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Το αντικείμενο δεδομένων γραμματοσειράς που περιέχει τις πληροφορίες για τη γραμματοσειρά [IFontData](../../ifontdata/). |
| fontStyle | [FontStyleType](../../fontstyletype/) | Το στυλ της γραμματοσειράς για το οποίο θα ανακτηθούν τα δεδομένα [FontStyleType](../../fontstyletype/). |

### Τιμή Επιστροφής

Ένας πίνακας byte που περιέχει τα δεδομένα γραμματοσειράς για το καθορισμένο στυλ γραμματοσειράς. Εάν τα δεδομένα γραμματοσειράς ή το στυλ δεν βρεθούν, επιστρέφει null.
## Παρατηρήσεις

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## Δείτε επίσης

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IFontData](../../ifontdata/)
* Κλάση [IFontsManager](../)
* Χώρος Ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)