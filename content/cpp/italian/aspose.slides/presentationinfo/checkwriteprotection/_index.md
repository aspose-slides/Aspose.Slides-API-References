---
title: CheckWriteProtection()
second_title: Riferimento API Aspose.Slides per C++
description: Verifica se una password per modificare è corretta per una presentazione protetta da scrittura.
type: docs
weight: 66
url: /it/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) metodo

Verifica se una password per modificare è corretta per una presentazione protetta da scrittura.

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | La password da verificare. |

### Valore di ritorno

True se la presentazione è write protected e la password è corretta. False altrimenti.

## Osservazioni

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. È consigliabile verificare la [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) proprietà prima di chiamare questo metodo.
1. Quando la password è null o vuota, questo metodo restituisce false.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [PresentationInfo](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)