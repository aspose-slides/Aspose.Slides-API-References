---
title: get_Sound()
second_title: Aspose.Slides για την τεκμηρίωση API του C++
description: Αντιπροσωπεύει τον ήχο αναπαραγωγής του υπερσυνδέσμου. Διαβάστε IAudio.
type: docs
weight: 287
url: /el/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() μέθοδος


Αντιπροσωπεύει τον ήχο αναπαραγωγής του υπερσυνδέσμου. Διαβάστε [IAudio](../../iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```

## Παρατηρήσεις



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Αποκτήστε τον πρώτο σύνδεσμο σχήματος
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Εξαγάγετε τον ήχο του υπερσυνδέσμου σε byte array
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAudio](../../iaudio/)
* Κλάση [Hyperlink](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)