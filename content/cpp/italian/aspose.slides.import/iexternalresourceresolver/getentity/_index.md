---
title: GetEntity()
second_title: Riferimento API Aspose.Slides per C++
description: Mappa un URI a un oggetto che contiene la risorsa effettiva.
type: docs
weight: 14
url: /it/aspose.slides.import/iexternalresourceresolver/getentity/
---
## IExternalResourceResolver::GetEntity(System::String) metodo

Mappa un URI a un oggetto che contiene la risorsa effettiva.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::IExternalResourceResolver::GetEntity(System::String absoluteUri)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | URI assoluto all'oggetto. |

### Valore di ritorno

Un oggetto [System::IO::Stream](../../../system.io/stream/) o null se la risorsa non può essere trasmessa.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [String](../../../system/string/)
* Classe [IExternalResourceResolver](../)
* Spazio dei nomi [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)