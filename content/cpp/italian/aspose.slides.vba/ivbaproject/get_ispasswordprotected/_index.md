---
title: get_IsPasswordProtected()
second_title: Riferimento API di Aspose.Slides per C++
description: Indica se il VBAProject è protetto da una password per visualizzare le proprietà del progetto. Sola lettura bool.
type: docs
weight: 40
url: /it/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() metodo


Indica se il VBAProject è protetto da una password per visualizzare le proprietà del progetto. Sola lettura **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
```

## Osservazioni



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## Vedi anche

* Classe [IVbaProject](../)
* Spazio dei nomi [Aspose::Slides::Vba](../../)
* Libreria [Aspose.Slides](../../../)