---
title: get_ReadOnlyRecommended()
second_title: Αναφορά API για Aspose.Slides σε C++
description: Λαμβάνει σύσταση μόνο για ανάγνωση. Διαβάζει bool.
type: docs
weight: 79
url: /el/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() μέθοδος

Λαμβάνει την σύσταση μόνο για ανάγνωση. Διαβάζει **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## Σχόλια

Ο παρακάτω κώδικας δείχνει πώς να ορίσετε ένα PowerPoint [Presentation](../../presentation/) σε Μόνο-Ανάγνωση σε C# χρησιμοποιώντας [Aspose.Slides](../../). 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [ProtectionManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)