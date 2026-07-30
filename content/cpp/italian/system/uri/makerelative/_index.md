---
title: MakeRelative()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina la differenza tra due istanze di Uri.
type: docs
weight: 365
url: /it/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) metodo

Determina la differenza tra due istanze di [Uri](../).

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'URI da confrontare con l'URI corrente |

### Valore di ritorno

Se il nome host e lo schema degli URI rappresentati dall'oggetto corrente e **toUri** sono gli stessi, questo metodo restituisce un [String](../../string/) che rappresenta un [Uri](../) relativo, che, aggiunto all'istanza URI corrente, produce **toUri**. Se il nome host o lo schema sono diversi, questo metodo restituisce un [String](../../string/) che rappresenta il parametro **uri**.

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Uri](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)