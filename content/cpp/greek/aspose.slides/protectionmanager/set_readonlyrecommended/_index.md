---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει τη σύσταση ανάγνωσης μόνο. Γράψτε bool.
type: docs
weight: 92
url: /el/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) μέθοδος

Ορίζει τη σύσταση ανάγνωσης μόνο. Γράψτε **bool**.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## Παρατηρήσεις

Ο παρακάτω κώδικας δείγματος δείχνει πώς να ορίσετε ένα PowerPoint [Presentation](../../presentation/) σε κατάσταση ανάγνωσης μόνο στο C# χρησιμοποιώντας το [Aspose.Slides](../../).
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [ProtectionManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)