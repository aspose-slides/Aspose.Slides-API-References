---
title: CheckWriteProtection()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica se una password per modificare è corretta per una presentazione protetta da scrittura.
type: docs
weight: 66
url: /it/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) metodo

Verifica se una password per modificare è corretta per una presentazione protetta da scrittura.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | La password da verificare. |

### Valore restituito

True se la presentazione è protetta da scrittura e la password è corretta. False altrimenti.

## Osservazioni

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. Si consiglia di verificare la proprietà [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) prima di chiamare questo metodo.
1. Quando la password è null o vuota, questo metodo restituisce false.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IPresentationInfo](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)