---
title: Uri()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit un objet Uri qui représente l'URI spécifié.
type: docs
weight: 287
url: /fr/system/uri/uri/
---
## Uri::Uri(const String\&) constructeur

Construit un objet [Uri](../) qui représente l'URI spécifié.

```cpp
System::Uri::Uri(const String &uriString)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | La chaîne URI à représenter par l'objet en cours de construction |

## Uri::Uri(const String\&, bool) constructeur

Construit un objet [Uri](../) qui représente l'URI spécifié ; un argument indique si l'URI doit être échappé.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | La chaîne URI à représenter par l'objet en cours de construction |
| dontEscape | **bool** | Indique si l'URI ne doit pas être échappé |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) constructeur

Construit un [Uri](../) à partir de l'objet [Uri](../) spécifié représentant l'URI de base et de la représentation sous forme de chaîne de l'URI relative ; un argument indique si l'URI doit être échappé.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'URI de base |
| relativeUri | const [String](../../string/)\& | L'URI relative qui est ajoutée à l'URI de base |
| dontEscape | **bool** | Indique si l'URI ne doit pas être échappé |

## Uri::Uri(const String\&, UriKind) constructeur

Construit un objet [Uri](../) qui représente l'URI spécifié ; un argument indique le type d'URI.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | La chaîne URI à représenter par l'objet en cours de construction |
| uriKind | [UriKind](../../urikind/) | Indique le type d'URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) constructeur

Construit un [Uri](../) à partir des URI de base et relatifs spécifiés.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'URI de base |
| relativeUri | const [String](../../string/)\& | L'URI relative qui est ajoutée à l'URI de base |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) constructeur

Construit un [Uri](../) à partir des URI de base et relatifs spécifiés.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'URI de base |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'URI relative qui est ajoutée à l'URI de base |

## Voir aussi

* Enumération [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Uri](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)