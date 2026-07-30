---
title: get_IsOnlyDocumentPropertiesLoaded()
second_title: Riferimento API Aspose.Slides per C++
description: Questa proprietà ha senso, se il file della presentazione è protetto da password e le proprietà del documento di questo file sono pubbliche. Il valore true indica che solo le proprietà del documento vengono caricate da un file di presentazione crittografato senza l'uso della password. Il valore false indica che l'intera presentazione crittografata viene caricata con l'uso della password corretta, non solo le proprietà del documento vengono caricate. Se la presentazione non è crittografata, il valore della proprietà è sempre false. Se le proprietà del documento di un file crittografato non sono pubbliche, il valore della proprietà è sempre false. Se PresentationEx.EncryptDocumentProperties è true, allora il valore della proprietà IsOnlyDocumentPropertiesLoaded è sempre false. Sola lettura bool.
type: docs
weight: 40
url: /it/aspose.slides/iprotectionmanager/get_isonlydocumentpropertiesloaded/
---
## IProtectionManager::get_IsOnlyDocumentPropertiesLoaded() metodo

Questa proprietà ha senso, se il file della presentazione è protetto da password e le proprietà del documento di questo file sono pubbliche. Il valore true indica che solo le proprietà del documento vengono caricate da un file di presentazione crittografato senza l'uso della password. Il valore false indica che l'intera presentazione crittografata viene caricata con l'uso della password corretta, non solo le proprietà del documento vengono caricate. Se la presentazione non è crittografata, il valore della proprietà è sempre false. Se le proprietà del documento di un file crittografato non sono pubbliche, il valore della proprietà è sempre false. Se PresentationEx.EncryptDocumentProperties è true, allora il valore della proprietà IsOnlyDocumentPropertiesLoaded è sempre false. Solo lettura **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_IsOnlyDocumentPropertiesLoaded()=0
```

## Vedi anche

* Classe [IProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)