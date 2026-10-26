---
title: CheckWriteProtection()
second_title: Riferimento API Aspose.Slides per C++
description: Determina se una presentazione è protetta da password per la modifica.
type: docs
weight: 157
url: /it/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) metodo

Determina se una presentazione è protetta da password per la modifica.

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | La password per la verifica. |

### Valore di ritorno

True se la password è valida; altrimenti, false.
## Osservazioni

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. È consigliabile verificare la proprietà [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) prima di chiamare questo metodo.
1. Quando la password è null o vuota, questo metodo restituisce false.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [ProtectionManager](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)