---
title: get_IsWriteProtected()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un valore che indica se una presentazione collegata è protetta da scrittura.
type: docs
weight: 27
url: /it/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() metodo

Restituisce un valore che indica se una presentazione collegata è protetta da scrittura.

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## Osservazioni



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Se la presentazione è protetta da una password per l'apertura, il valore della proprietà è uguale a NotDefined. 
## Vedi anche

* Enum [NullableBool](../../nullablebool/)
* Classe [PresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)