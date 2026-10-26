---
title: RegisterPrefix()
second_title: Riferimento API di Aspose.Slides per C++
description: Registra il discendente WebRequest per l'URI specificato.
type: docs
weight: 92
url: /it/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) metodo

Registra il discendente [WebRequest](../) per l'URI specificato.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | L'URI o il prefisso dell'URI. |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | Crea nuove istanze della classe [WebRequest](../). |

### Valore restituito

True quando il discendente [WebRequest](../) è registrato correttamente per l'URI specificato, altrimenti false.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [IWebRequestCreate](../../iwebrequestcreate/)
* Classe [WebRequest](../)
* Namespace [System::Net](../../)
* Libreria [Aspose.Slides](../../../)