---
title: Trim()
second_title: Référence API Aspose.Slides pour C++
description: Supprime tous les caractères d'espacement du début et de la fin de la chaîne.
type: docs
weight: 677
url: /fr/system/string/trim/
---
## String::Trim() const méthode

Supprime tous les caractères d'espacement du début et de la fin de la chaîne.

```cpp
String System::String::Trim() const
```

### Valeur de retour

[String](../) sans espaces au début ni à la fin.

## String::Trim(char_t) const méthode

Supprime toutes les occurrences du caractère fourni au début et à la fin de la chaîne.

```cpp
String System::String::Trim(char_t ch) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| ch | char_t | Symbole à supprimer. |

### Valeur de retour

Résultat de la suppression.

## String::Trim(const String\&) const méthode

Supprime toutes les occurrences des caractères fournis au début et à la fin de la chaîne.

```cpp
String System::String::Trim(const String &anyOf) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) de caractères à supprimer. |

### Valeur de retour

[String](../) sans les caractères supprimés.

## String::Trim(const ArrayPtr\<char_t\>\&) const méthode

Supprime toutes les occurrences des caractères fournis au début et à la fin de la chaîne.

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caractères à supprimer. |

### Valeur de retour

[String](../) sans les caractères supprimés.

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)