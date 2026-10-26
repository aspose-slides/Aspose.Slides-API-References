---
title: get_IsWriteProtected()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce un valore che indica se una presentazione collegata è protetta da scrittura.
type: docs
weight: 27
url: /it/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() metodo


Restituisce un valore che indica se una presentazione collegata è protetta da scrittura.

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## Note



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Se la presentazione è protetta da una password per l'apertura, il valore della proprietà è uguale a NotDefined. Vedi l'enumerazione [NullableBool](../../nullablebool/). 

## Vedere anche

* Enum [NullableBool](../../nullablebool/)
* Classe [IPresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)