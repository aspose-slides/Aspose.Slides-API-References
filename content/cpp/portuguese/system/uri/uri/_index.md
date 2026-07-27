---
title: Uri()
second_title: Referência da API Aspose.Slides para C++
description: Constrói um objeto Uri que representa o URI especificado.
type: docs
weight: 287
url: /pt/system/uri/uri/
---
## Uri::Uri(const String\&) construtor

Constrói um objeto [Uri](../) que representa o URI especificado.

```cpp
System::Uri::Uri(const String &uriString)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | The string URI to be represented by the object being constructed |

## Uri::Uri(const String\&, bool) construtor

Constrói um objeto [Uri](../) que representa o URI especificado; um argumento especifica se o URI deve ser escapado.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | The string URI to be represented by the object being constructed |
| dontEscape | **bool** | Especifica se o URI não deve ser escapado |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) construtor

Constrói um [Uri](../) a partir do [Uri](../) especificado que representa o URI base e a representação em string do URI relativo; um argumento especifica se o URI deve ser escapado.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | O URI base |
| relativeUri | const [String](../../string/)\& | O URI relativo que é adicionado ao URI base |
| dontEscape | **bool** | Especifica se o URI não deve ser escapado |

## Uri::Uri(const String\&, UriKind) construtor

Constrói um objeto [Uri](../) que representa o URI especificado; um argumento especifica o tipo de URI.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | The string URI to be represented by the object being constructed |
| uriKind | [UriKind](../../urikind/) | Especifica o tipo de URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) construtor

Constrói um [Uri](../) a partir dos URIs base e relativo especificados.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | O URI base |
| relativeUri | const [String](../../string/)\& | O URI relativo que é adicionado ao URI base |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) construtor

Constrói um [Uri](../) a partir dos URIs base e relativo especificados.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | O URI base |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | O URI relativo que é adicionado ao URI base |

## Veja Também

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)