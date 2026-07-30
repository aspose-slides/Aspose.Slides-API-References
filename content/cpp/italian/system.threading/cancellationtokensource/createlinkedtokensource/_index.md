---
title: CreateLinkedTokenSource()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una sorgente di token collegata che viene annullata quando uno qualsiasi dei token forniti viene annullato.
type: docs
weight: 66
url: /it/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) metodo


Crea una sorgente di token collegata che viene annullata quando uno qualsiasi dei token forniti viene annullato.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | Primo token di cancellazione da monitorare. |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | Secondo token di cancellazione da monitorare. |

### Valore restituito

Nuova sorgente di token che verrà annullata quando uno dei token di input viene annullato.

## Osservazioni



La sorgente restituita verrà annullata immediatamente se uno dei token di input è già annullato. 

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [CancellationTokenSource](../)
* Classe [CancellationToken](../../cancellationtoken/)
* Spazio dei nomi [System::Threading](../../)
* Libreria [Aspose.Slides](../../../)