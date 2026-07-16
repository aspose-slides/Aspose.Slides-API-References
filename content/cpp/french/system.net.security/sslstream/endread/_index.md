---
title: EndRead()
second_title: Référence API Aspose.Slides pour C++
description: Attend jusqu'à ce que l'opération de lecture asynchrone spécifiée soit terminée.
type: docs
weight: 430
url: /fr/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) method


Attend jusqu'à ce que l'opération de lecture asynchrone spécifiée soit terminée.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous read operation |

### Valeur de retour

Le nombre d'octets lus pendant l'opération de lecture représentée par **asyncResult**

## Voir également

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [SslStream](../)
* Espace de noms [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)