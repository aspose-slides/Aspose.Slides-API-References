---
title: SetWriteProtection()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίστε προστασία εγγραφής για αυτήν την παρουσίαση με τον καθορισμένο κωδικό πρόσβασης.
type: docs
weight: 131
url: /el/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) μέθοδος

Ορίστε την προστασία εγγραφής για αυτήν την παρουσίαση με τον καθορισμένο κωδικό πρόσβασης.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Ο κωδικός πρόσβασης. |
## Παρατηρήσεις

Ο παρακάτω κώδικας δείχνει πώς να ορίσετε προστασία εγγραφής σε μια παρουσίαση.
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [ProtectionManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)