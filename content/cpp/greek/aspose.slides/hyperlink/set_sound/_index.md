---
title: set_Sound()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Αναπαριστά τον ήχο αναπαραγωγής του υπερσυνδέσμου. Γράψτε IAudio.
type: docs
weight: 300
url: /el/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) μέθοδος


Αναπαριστά τον ήχο αναπαραγωγής του υπερσυνδέσμου. Γράψτε [IAudio](../../iaudio/).

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## Παρατηρήσεις



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Λάβετε τον πρώτο υπερσύνδεσμο του σχήματος
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Εξάγετε τον ήχο του υπερσυνδέσμου σε πίνακα byte
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAudio](../../iaudio/)
* Κλάση [Hyperlink](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)