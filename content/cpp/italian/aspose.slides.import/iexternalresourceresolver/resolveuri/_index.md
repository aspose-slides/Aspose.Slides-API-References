---
title: ResolveUri()
second_title: Riferimento API Aspose.Slides per C++
description: Risolve l'URI assoluto a partire dall'URI di base e da quello relativo.
type: docs
weight: 1
url: /it/aspose.slides.import/iexternalresourceresolver/resolveuri/
---
## IExternalResourceResolver::ResolveUri(System::String, System::String) metodo

Risolvi l'URI assoluto a partire dall'URI di base e da quello relativo.

```cpp
virtual System::String Aspose::Slides::Import::IExternalResourceResolver::ResolveUri(System::String baseUri, System::String relativeUri)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseUri | [System::String](../../../system/string/) | URI di base degli oggetti di collegamento |
| relativeUri | [System::String](../../../system/string/) | URI relativo all'oggetto collegato. |

### Valore restituito

URI assoluto o null se l'URI relativo non può essere risolto.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IExternalResourceResolver](../)
* Spazio dei nomi [Aspose::Slides::Import](../../)
* Libreria [Aspose.Slides](../../../)