---
title: Encrypt()
second_title: Aspose.Slides για C++ API Αναφορά
description: Κρυπτογραφεί την παρουσίαση με τον καθορισμένο κωδικό πρόσβασης.
type: docs
weight: 105
url: /el/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) μέθοδος

Κρυπτογραφεί [Presentation](../../presentation/) με καθορισμένο κωδικό πρόσβασης.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | Ο κωδικός πρόσβασης. |
## Παρατηρήσεις

Ο παρακάτω κώδικας δείγματος δείχνει πώς να κρυπτογραφήσετε ένα PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [ProtectionManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)