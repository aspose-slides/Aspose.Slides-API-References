---
title: get_IsValid()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αν αυτή η ψηφιακή υπογραφή είναι έγκυρη και το έγγραφο δεν έχει παραβιαστεί, αυτή η τιμή θα είναι true. Μόνο για ανάγνωση bool.
type: docs
weight: 14
url: /el/aspose.slides/idigitalsignature/get_isvalid/
---
## IDigitalSignature::get_IsValid() μέθοδος

If this digital signature is valid and the document has not been tampered with, this value will be true. Read-only **bool**.

```cpp
virtual bool Aspose::Slides::IDigitalSignature::get_IsValid()=0
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

* Κλάση [IDigitalSignature](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)