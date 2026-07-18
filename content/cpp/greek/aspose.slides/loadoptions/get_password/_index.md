---
title: get_Password()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Λαμβάνει τον κωδικό πρόσβασης. Διαβάστε System::String."
type: docs
weight: 105
url: /el/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() μέθοδος

Λαμβάνει τον κωδικό πρόσβασης. Διαβάστε [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## Παρατηρήσεις

Ο κωδικός πρόσβασης.

Ο παρακάτω κώδικας δείγματος δείχνει πώς να ανοίξετε το PowerPoint [Presentation](../../presentation/) προστατευμένο με κωδικό πρόσβασης. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [LoadOptions](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)