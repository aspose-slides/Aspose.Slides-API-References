---
title: GetEntity()
second_title: Riferimento API Aspose.Slides per C++
description: Mappa un URI a un oggetto contenente la risorsa effettiva.
type: docs
weight: 14
url: /it/aspose.slides.import/externalresourceresolver/getentity/
---
## ExternalResourceResolver::GetEntity(System::String) metodo


Mappa un URI a un oggetto contenente la risorsa effettiva.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::ExternalResourceResolver::GetEntity(System::String absoluteUri) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | URI assoluto per l'oggetto. |

### Valore di ritorno

Un oggetto [System::IO::Stream](../../../system.io/stream/) o null se la risorsa non può essere trasmessa.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [String](../../../system/string/)
* Classe [ExternalResourceResolver](../)
* Spazio dei nomi [Aspose::Slides::Import](../../)
* Libreria [Aspose.Slides](../../../)