---
title: get_SignTime()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Ο χρόνος κατά τον οποίο υπογράφηκε το έγγραφο. Μόνο για ανάγνωση System::DateTime."
type: docs
weight: 27
url: /el/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() μέθοδος


Ο χρόνος κατά τον οποίο υπογράφηκε το έγγραφο. Μόνο για ανάγνωση [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## Παρατηρήσεις



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(u"Signature check: {0}, Signing time: {1}",
        (signature->get_IsValid() ? u"VALID" : u"INVALID"),
        signature->get_SignTime()
    );
}
```

## Δείτε επίσης

* Κλάση [DateTime](../../../system/datetime/)
* Κλάση [DigitalSignature](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)