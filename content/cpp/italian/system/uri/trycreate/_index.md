---
title: TryCreate()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un oggetto Uri che rappresenta l'URI specificato; un argomento specifica il tipo di URI.
type: docs
weight: 508
url: /it/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) metodo


Crea un oggetto [Uri](../) che rappresenta l'URI specificato; un argomento specifica il tipo di URI.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | La stringa URI da rappresentare nell'oggetto in costruzione |
| uriKind | [UriKind](../../urikind/) | Specifica il tipo di URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'argomento di output che, se la costruzione riesce, punta al nuovo oggetto [Uri](../) creato al ritorno del metodo |

### Valore di ritorno

True se la costruzione è riuscita, altrimenti - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) metodo


Crea un oggetto [Uri](../) dall'oggetto [Uri](../) specificato che rappresenta l'URI base e dalla rappresentazione stringa dell'URI relativo.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'URI base |
| relativeUri | const [String](../../string/)\& | L'URI relativo che viene aggiunto all'URI base |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'argomento di output che, se la costruzione riesce, punta al nuovo oggetto [Uri](../) creato al ritorno del metodo |

### Valore di ritorno

True se la costruzione è riuscita, altrimenti - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) metodo


Crea un oggetto [Uri](../) dagli URI base e relativi specificati.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'URI base |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'URI relativo che viene aggiunto all'URI base |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'argomento di output che, se la costruzione riesce, punta al nuovo oggetto [Uri](../) creato al ritorno del metodo |

### Valore di ritorno

True se la costruzione è riuscita, altrimenti - false

## Vedi anche

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Uri](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)