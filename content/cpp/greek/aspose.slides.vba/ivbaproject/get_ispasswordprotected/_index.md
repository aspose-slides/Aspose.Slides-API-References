---
title: get_IsPasswordProtected()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δείχνει εάν το VBAProject προστατεύεται με κωδικό πρόσβασης για προβολή ιδιοτήτων του έργου. Μόνοανάγνωση bool.
type: docs
weight: 40
url: /el/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() μέθοδος


Δείχνει εάν το VBAProject προστατεύεται με κωδικό πρόσβασης για προβολή ιδιοτήτων του έργου. Μόνοανάγνωση **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
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

* Κλάση [IVbaProject](../)
* Χώρος ονομάτων [Aspose::Slides::Vba](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)