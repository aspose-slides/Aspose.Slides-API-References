---
title: TryCreate()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit un objet Uri qui représente l'URI spécifié ; un argument indique le type d'URI.
type: docs
weight: 508
url: /fr/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) méthode

Construit un objet [Uri](../) qui représente l'URI spécifié; un argument spécifie le type d'URI.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | La chaîne URI à représenter par l'objet en cours de construction |
| uriKind | [UriKind](../../urikind/) | Spécifie le type d'URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'argument de sortie qui, si la construction réussit, pointe vers le nouvel objet [Uri](../) construit lors du retour de la méthode |

### Valeur de retour

Vrai si la construction a réussi, sinon - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) méthode

Construit un [Uri](../) objet à partir de l'objet [Uri](../) spécifié représentant l'URI de base et de la représentation sous forme de chaîne de l'URI relative.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'URI de base |
| relativeUri | const [String](../../string/)\& | L'URI relative qui est ajouté à l'URI de base |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'argument de sortie qui, si la construction réussit, pointe vers le nouvel objet [Uri](../) construit lors du retour de la méthode |

### Valeur de retour

Vrai si la construction a réussi, sinon - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) méthode

Construit un [Uri](../) objet à partir des URIs de base et relative spécifiées.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'URI de base |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'URI relative qui est ajouté à l'URI de base |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'argument de sortie qui, si la construction réussit, pointe vers le nouvel objet [Uri](../) construit lors du retour de la méthode |

### Valeur de retour

Vrai si la construction a réussi, sinon - false

## Voir également

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)