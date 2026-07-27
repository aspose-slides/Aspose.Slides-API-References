---
title: TryCreate()
second_title: Referência da API Aspose.Slides para C++
description: Constrói um objeto Uri que representa o URI especificado; um argumento especifica o tipo de URI.
type: docs
weight: 508
url: /pt/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) method

Constrói um objeto [Uri](../) que representa o URI especificado; um argumento especifica o tipo de URI.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | A string URI a ser representada pelo objeto sendo construído |
| uriKind | [UriKind](../../urikind/) | Especifica o tipo de URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | O argumento de saída que, se a construção for bem-sucedida, aponta para o novo objeto [Uri](../) construído ao retornar o método |

### Valor de Retorno

True se a construção for bem-sucedida, caso contrário - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) method

Constrói um objeto [Uri](../) a partir do objeto [Uri](../) especificado que representa o URI base e a representação em string do URI relativo.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | O URI base |
| relativeUri | const [String](../../string/)\& | O URI relativo que é adicionado ao URI base |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | O argumento de saída que, se a construção for bem-sucedida, aponta para o novo objeto [Uri](../) construído ao retornar o método |

### Valor de Retorno

True se a construção for bem-sucedida, caso contrário - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) method

Constrói um objeto [Uri](../) a partir dos URIs base e relativo especificados.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | O URI base |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | O URI relativo que é adicionado ao URI base |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | O argumento de saída que, se a construção for bem-sucedida, aponta para o novo objeto [Uri](../) construído ao retornar o método |

### Valor de Retorno

True se a construção for bem-sucedida, caso contrário - false

## Veja Também

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Uri](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)