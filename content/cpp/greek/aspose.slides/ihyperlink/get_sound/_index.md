---
title: get_Sound()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αντιπροσωπεύει τον ήχο αναπαραγωγής του υπερσυνδέσμου. Διαβάστε IAudio.
type: docs
weight: 183
url: /el/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() μέθοδος


Αντιπροσωπεύει τον ήχο αναπαραγωγής του υπερσυνδέσμου. Διαβάστε [IAudio](../../iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
```

## Σχόλια



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Λάβετε το πρώτο υπερσύνδεσμο σχήματος
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
* Βιβλιοθήκη [Aspose.Slides](../../../)