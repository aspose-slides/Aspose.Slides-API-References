---
title: FindHeader()
second_title: Riferimento API Aspose.Slides per C++
description: Trova la mappatura dell'intestazione per il tipo di intestazione specificato.
type: docs
weight: 352
url: /it/system.web.services.protocols/soapmessage/findheader/
---
## SoapMessage::FindHeader(System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, const TypeInfo\&) method

Trova la mappatura dell'intestazione per il tipo di intestazione specificato.

```cpp
System::SharedPtr<SoapHeaderMapping> System::Web::Services::Protocols::SoapMessage::FindHeader(System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headersInfo, const TypeInfo &headerType)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| headersInfo | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | La raccolta delle mappature delle intestazioni. |
| headerType | const [TypeInfo](../../../system/typeinfo/)\& | Il tipo di intestazione da cercare. |

### Valore restituito

La mappatura dell'intestazione.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [SoapMessage](../)
* Namespace [System::Web::Services::Protocols](../../)
* Libreria [Aspose.Slides](../../../)