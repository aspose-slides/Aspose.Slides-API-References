---
title: CheckWriteProtection()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se una presentazione è protetta da password per la modifica.
type: docs
weight: 157
url: /it/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) metodo


Determina se una presentazione è protetta da password per la modifica.

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | La password per il controllo. |

### Valore di ritorno

True se la password è valida; altrimenti, false.
## Note



```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```



1. Dovresti controllare la proprietà [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) prima di chiamare questo metodo.
1. Quando la password è null o vuota, questo metodo restituisce false.


## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)