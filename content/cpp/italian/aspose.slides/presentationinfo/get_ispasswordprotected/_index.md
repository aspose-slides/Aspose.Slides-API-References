---
title: get_IsPasswordProtected()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un valore che indica se una presentazione collegata è protetta da una password per l'apertura.
type: docs
weight: 14
url: /it/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() metodo


Restituisce un valore che indica se una presentazione collegata è protetta da una password per l'apertura.

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## Osservazioni



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## Vedi anche

* Classe [PresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)