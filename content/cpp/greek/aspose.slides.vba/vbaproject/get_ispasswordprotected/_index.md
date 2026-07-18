---
title: get_IsPasswordProtected()
second_title: Αναφορά API Aspose.Slides για C++
description: Δείχνει εάν το VBAProject προστατεύεται με κωδικό πρόσβασης για την προβολή των ιδιοτήτων του έργου. Μόνο για ανάγνωση bool.
type: docs
weight: 40
url: /el/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() μέθοδος

Δείχνει εάν το VBAProject προστατεύεται με κωδικό πρόσβασης για την προβολή των ιδιοτήτων του έργου. Μόνο για ανάγνωση **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```

## Σχόλια

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## Δείτε επίσης

* Κλάση [VbaProject](../)
* Χώρος ονομάτων [Aspose::Slides::Vba](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)