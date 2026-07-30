---
title: IsBypassed()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un valore che indica se il proxy non deve essere utilizzato per l'host specificato.
type: docs
weight: 40
url: /it/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed(System::SharedPtr\<Uri\>) metodo


Restituisce un valore che indica se il proxy non deve essere utilizzato per l'host specificato.

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| host | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI dell'host da verificare. |

### Valore di ritorno

True quando il server proxy non deve essere utilizzato, altrimenti false.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [IWebProxy](../)
* Spazio dei nomi [System::Net](../../)
* Libreria [Aspose.Slides](../../../)