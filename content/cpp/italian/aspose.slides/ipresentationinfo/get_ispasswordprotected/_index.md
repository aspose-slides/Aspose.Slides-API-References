---
title: get_IsPasswordProtected()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene un valore che indica se una presentazione collegata è protetta da una password per l'apertura.
type: docs
weight: 14
url: /it/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() metodo


Ottiene un valore che indica se una presentazione collegata è protetta da una password per l'apertura.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## Osservazioni



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## Vedi anche

* Classe [IPresentationInfo](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)