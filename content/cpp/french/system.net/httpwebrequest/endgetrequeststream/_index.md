---
title: EndGetRequestStream()
second_title: Référence API Aspose.Slides for C++
description: Attend que l'opération asynchrone spécifiée pour obtenir un flux se termine.
type: docs
weight: 482
url: /fr/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) méthode

Attend que l'opération asynchrone spécifiée pour obtenir un flux se termine.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un [IAsyncResult](../../../system/iasyncresult/) objet qui représente une opération asynchrone pour obtenir un flux. |

### Valeur de retour

Le flux pour écrire des données vers la ressource.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [HttpWebRequest](../)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)