---
title: get_ReadOnlyRecommended()
second_title: Αναφορά API Aspose.Slides για C++
description: Λαμβάνει τη σύσταση μόνο για ανάγνωση. Διαβάζει bool.
type: docs
weight: 79
url: /el/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() μέθοδος

Λαμβάνει τη σύσταση μόνο για ανάγνωση. Διαβάζει **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
```

## Παρατηρήσεις



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [IProtectionManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)