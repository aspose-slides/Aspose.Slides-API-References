---
title: Uri()
second_title: Riferimento API Aspose.Slides per C++
description: Costruisce un oggetto Uri che rappresenta l'URI specificato.
type: docs
weight: 287
url: /it/system/uri/uri/
---
## Uri::Uri(const String\&) costruttore

Crea un oggetto [Uri](../) che rappresenta l'URI specificato.

```cpp
System::Uri::Uri(const String &uriString)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | La stringa URI da rappresentare nell'oggetto in fase di costruzione |

## Uri::Uri(const String\&, bool) costruttore

Crea un oggetto [Uri](../) che rappresenta l'URI specificato; un argomento specifica se l'URI deve essere codificato.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | La stringa URI da rappresentare nell'oggetto in fase di costruzione |
| dontEscape | **bool** | Specifica se l'URI non deve essere codificato |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) costruttore

Crea un [Uri](../) oggetto dall'[Uri](../) specificato che rappresenta l'URI di base e dalla rappresentazione stringa dell'URI relativo; un argomento specifica se l'URI deve essere codificato.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'URI di base |
| relativeUri | const [String](../../string/)\& | L'URI relativo che viene aggiunto all'URI di base |
| dontEscape | **bool** | Specifica se l'URI non deve essere codificato |

## Uri::Uri(const String\&, UriKind) costruttore

Crea un oggetto [Uri](../) che rappresenta l'URI specificato; un argomento specifica il tipo di URI.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | La stringa URI da rappresentare nell'oggetto in fase di costruzione |
| uriKind | [UriKind](../../urikind/) | Specifica il tipo di URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) costruttore

Crea un [Uri](../) oggetto dagli URI di base e relativo specificati.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'URI di base |
| relativeUri | const [String](../../string/)\& | L'URI relativo che viene aggiunto all'URI di base |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) costruttore

Crea un [Uri](../) oggetto dagli URI di base e relativo specificati.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'URI di base |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'URI relativo che viene aggiunto all'URI di base |

## Vedi anche

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)