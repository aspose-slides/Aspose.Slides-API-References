---
title: get_IsOnlyDocumentPropertiesLoaded()
second_title: Riferimento API di Aspose.Slides per C++
description: Questa proprietà è significativa se il file di presentazione è protetto da password e le proprietà del documento di questo file sono pubbliche. Un valore true indica che solo le proprietà del documento vengono caricate da un file di presentazione crittografato senza l'uso della password. Un valore false indica che l'intera presentazione crittografata viene caricata con l'uso della password corretta, non solo le proprietà del documento. Se la presentazione non è crittografata, il valore della proprietà è sempre false. Se le proprietà del documento di un file crittografato non sono pubbliche, il valore della proprietà è sempre false. Se Presentation.EncryptDocumentProperties è true, allora il valore della proprietà IsOnlyDocumentPropertiesLoaded è sempre false. Solo lettura bool.
type: docs
weight: 40
url: /it/aspose.slides/protectionmanager/get_isonlydocumentpropertiesloaded/
---
## ProtectionManager::get_IsOnlyDocumentPropertiesLoaded() metodo

Questa proprietà ha senso se il file di presentazione è protetto da password e le proprietà del documento di questo file sono pubbliche. Un valore true indica che solo le proprietà del documento vengono caricate da un file di presentazione crittografato senza l'uso della password. Un valore false indica che l'intera presentazione crittografata viene caricata utilizzando la password corretta, non solo le proprietà del documento. Se la presentazione non è crittografata, il valore della proprietà è sempre false. Se le proprietà del documento di un file crittografato non sono pubbliche, il valore della proprietà è sempre false. Se Presentation.EncryptDocumentProperties è true, allora il valore della proprietà IsOnlyDocumentPropertiesLoaded è sempre false. Solo lettura **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_IsOnlyDocumentPropertiesLoaded() override
```

## Vedi anche

* Classe [ProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)