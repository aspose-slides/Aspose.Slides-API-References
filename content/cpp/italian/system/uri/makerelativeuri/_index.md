---
title: MakeRelativeUri()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina la differenza tra gli URI rappresentati dall'oggetto corrente e dagli oggetti Uri specificati.
type: docs
weight: 352
url: /it/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) metodo


Determina la differenza tra gli URI rappresentati dall'oggetto corrente e dagli oggetti [Uri](../) specificati.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Il comparando |

### Valore restituito

Se il nome host e lo schema degli URI rappresentati dall'oggetto corrente e da **toUri** sono gli stessi, questo metodo restituisce un [Uri](../) relativo che, quando aggiunto all'istanza URI corrente, produce **toUri**. Se il nome host o lo schema sono diversi, questo metodo restituisce un oggetto [Uri](../) che rappresenta il parametro **uri**.

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)