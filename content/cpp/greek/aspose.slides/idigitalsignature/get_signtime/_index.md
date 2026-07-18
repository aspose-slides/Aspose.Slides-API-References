---
title: get_SignTime()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Ο χρόνος κατά τον οποίο υπογράφηκε το έγγραφο. Μόνο για ανάγνωση System::DateTime."
type: docs
weight: 27
url: /el/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() μέθοδος

Ο χρόνος κατά τον οποίο υπογράφηκε το έγγραφο. Μόνο για ανάγνωση [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## Παρατηρήσεις


```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## Δείτε επίσης

* Κλάση [DateTime](../../../system/datetime/)
* Κλάση [IDigitalSignature](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)