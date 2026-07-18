---
title: get_IsValid()
second_title: Αναφορά API Aspose.Slides για C++
description: Εάν αυτή η ψηφιακή υπογραφή είναι έγκυρη και το έγγραφο δεν έχει παραβιαστεί, αυτή η τιμή θα είναι αληθής. Μόνο για ανάγνωση bool.
type: docs
weight: 14
url: /el/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() μέθοδος


Εάν αυτή η ψηφιακή υπογραφή είναι έγκυρη και το έγγραφο δεν έχει παραβιαστεί, αυτή η τιμή θα είναι αληθής. Μόνο για ανάγνωση **bool**.

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
```

## Παρατηρήσεις



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## Δείτε επίσης

* Κλάση [DigitalSignature](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)