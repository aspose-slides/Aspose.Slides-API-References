---
title: RemoveWriteProtection()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αφαιρεί την προστασία εγγραφής για αυτήν την παρουσίαση.
type: docs
weight: 144
url: /el/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() μέθοδος

Αφαιρεί την προστασία εγγραφής για αυτήν την παρουσίαση.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## Παρατηρήσεις

Αυτό το παράδειγμα κώδικα σας δείχνει πώς να αφαιρέσετε την προστασία εγγραφής από ένα PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [ProtectionManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)