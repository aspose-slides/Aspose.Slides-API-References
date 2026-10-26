---
title: set_Password()
second_title: Aspose.Slides για C++ API Reference
description: "Ορίζει τον κωδικό πρόσβασης. Γράψτε System::String."
type: docs
weight: 118
url: /el/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) μέθοδος


Ορίζει τον κωδικό πρόσβασης. Γράψτε [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## Παρατηρήσεις


Ο κωδικός πρόσβασης. 

Ο παρακάτω κώδικας δείγματος δείχνει πώς να ανοίξετε ένα PowerPoint προστατευμένο με κωδικό [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// εργαστείτε με την αποκρυπτογραφημένη παρουσίαση
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [LoadOptions](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)