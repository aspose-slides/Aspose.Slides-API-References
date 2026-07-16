---
title: TrimStart()
second_title: Référence API Aspose.Slides pour C++
description: Supprime tous les caractères d'espace du début de la chaîne.
type: docs
weight: 690
url: /fr/system/string/trimstart/
---
## String::TrimStart() const méthode

Supprime tous les caractères d’espace du début de la chaîne.

```cpp
String System::String::TrimStart() const
```

### Valeur de retour

[String](../) sans espaces au début.

## String::TrimStart(char_t) const méthode

Supprime toutes les occurrences du caractère passé du début de la chaîne.

```cpp
String System::String::TrimStart(char_t ch) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| ch | char_t | Symbole à supprimer. |

### Valeur de retour

Résultat de la suppression.

## String::TrimStart(const String\&) const méthode

Supprime toutes les occurrences des caractères passés du début de la chaîne.

```cpp
String System::String::TrimStart(const String &anyOf) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) des caractères à supprimer. |

### Valeur de retour

[String](../) sans les caractères supprimés.

## String::TrimStart(const ArrayPtr\<char_t\>\&) const méthode

Supprime toutes les occurrences des caractères passés du début de la chaîne.

```cpp
String System::String::TrimStart(const ArrayPtr<char_t> &anyOf) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) des caractères à supprimer. |

### Valeur de retour

[String](../) sans les caractères supprimés.

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)