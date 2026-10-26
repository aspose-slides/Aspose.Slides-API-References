---
title: get_IsPasswordProtected()
second_title: Riferimento API di Aspose.Slides per C++
description: Indica se il VBAProject è protetto da una password per visualizzare le proprietà del progetto. Solo lettura bool.
type: docs
weight: 40
url: /it/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() metodo


Indica se il VBAProject è protetto da una password per visualizzare le proprietà del progetto. Solo lettura **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
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

* Classe [VbaProject](../)
* Spazio dei nomi [Aspose::Slides::Vba](../../)
* Libreria [Aspose.Slides](../../../)