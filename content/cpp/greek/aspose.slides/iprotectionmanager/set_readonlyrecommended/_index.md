---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides για την αναφορά API του C++
description: Ορίζει την προτεινόμενη ανάγνωση μόνο. Γράψτε bool.
type: docs
weight: 92
url: /el/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) μέθοδος

Ορίζει την προτεινόμενη ανάγνωση μόνο. Γράψτε **bool**.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
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