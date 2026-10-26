---
title: Uri()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye un objeto Uri que representa el URI especificado.
type: docs
weight: 287
url: /es/system/uri/uri/
---
## Uri::Uri(const String\&) constructor

Construye un objeto [Uri](../) que representa el URI especificado.

```cpp
System::Uri::Uri(const String &uriString)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | La cadena URI que será representada por el objeto que se está construyendo |

## Uri::Uri(const String\&, bool) constructor

Construye un objeto [Uri](../) que representa el URI especificado; un argumento indica si el URI debe escaparse.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | La cadena URI que será representada por el objeto que se está construyendo |
| dontEscape | **bool** | Indica si el URI no debe escaparse |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) constructor

Construye un [Uri](../) abject a partir del objeto [Uri](../) especificado que representa el URI base y la representación en cadena del URI relativo; un argumento indica si el URI debe escaparse.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | El URI base |
| relativeUri | const [String](../../string/)\& | El URI relativo que se añade al URI base |
| dontEscape | **bool** | Indica si el URI no debe escaparse |

## Uri::Uri(const String\&, UriKind) constructor

Construye un objeto [Uri](../) que representa el URI especificado; un argumento indica el tipo de URI.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | La cadena URI que será representada por el objeto que se está construyendo |
| uriKind | [UriKind](../../urikind/) | Indica el tipo de URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) constructor

Construye un [Uri](../) abject a partir de los URIs base y relativo especificados.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | El URI base |
| relativeUri | const [String](../../string/)\& | El URI relativo que se añade al URI base |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) constructor

Construye un [Uri](../) abject a partir de los URIs base y relativo especificados.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | El URI base |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | El URI relativo que se añade al URI base |

## See Also

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)