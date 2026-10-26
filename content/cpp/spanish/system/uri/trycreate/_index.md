---
title: TryCreate()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye un objeto Uri que representa el URI especificado; un argumento especifica el tipo de URI.
type: docs
weight: 508
url: /es/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) method

Construye un objeto [Uri](../) que representa el URI especificado; un argumento especifica el tipo de URI.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | La cadena URI que será representada por el objeto que se está construyendo |
| uriKind | [UriKind](../../urikind/) | Especifica el tipo de URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | El argumento de salida que, si la construcción tiene éxito, apunta al nuevo objeto [Uri](../) creado al regresar del método |

### Valor devuelto

True si la construcción tuvo éxito, de lo contrario - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) method

Construye un objeto [Uri](../) a partir del objeto [Uri](../) especificado que representa el URI base y la representación en cadena del URI relativo.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | El URI base |
| relativeUri | const [String](../../string/)\& | El URI relativo que se agrega al URI base |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | El argumento de salida que, si la construcción tiene éxito, apunta al nuevo objeto [Uri](../) creado al regresar del método |

### Valor devuelto

True si la construcción tuvo éxito, de lo contrario - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) method

Construye un objeto [Uri](../) a partir de los URIs base y relativo especificados.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | El URI base |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | El URI relativo que se agrega al URI base |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | El argumento de salida que, si la construcción tiene éxito, apunta al nuevo objeto [Uri](../) creado al regresar del método |

### Valor devuelto

True si la construcción tuvo éxito, de lo contrario - false

## See Also

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)