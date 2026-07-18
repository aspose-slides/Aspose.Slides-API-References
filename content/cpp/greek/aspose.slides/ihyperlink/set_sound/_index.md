---
title: set_Sound()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναπαριστά τον ήχο αναπαραγωγής του υπερσυνδέσμου. Γράψτε IAudio.
type: docs
weight: 196
url: /el/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) μέθοδος


Αναπαριστά τον ήχο αναπαραγωγής του υπερσυνδέσμου. Γράψτε [IAudio](../../iaudio/).

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
```

## Σχόλια


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Λάβετε τον πρώτο υπερσύνδεσμο σχήματος
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
* Κλάση [IHyperlink](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)