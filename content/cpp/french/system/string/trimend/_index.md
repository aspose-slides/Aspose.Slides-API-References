---
title: TrimEnd()
second_title: Référence API Aspose.Slides pour C++
description: Supprime tous les caractères d'espace blanc à la fin de la chaîne.
type: docs
weight: 703
url: /fr/system/string/trimend/
---
## String::TrimEnd() const méthode

Supprime tous les caractères d'espace blanc à la fin de la chaîne.

```cpp
String System::String::TrimEnd() const
```

### Valeur de retour

[String](../) sans espaces blancs au début.

## String::TrimEnd(char_t) const méthode

Supprime toutes les occurrences du caractère passé à la fin de la chaîne.

```cpp
String System::String::TrimEnd(char_t ch) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| ch | char_t | Symbole à supprimer. |

### Valeur de retour

Résultat de la suppression.

## String::TrimEnd(const String\&) const méthode

Supprime toutes les occurrences des caractères passés à la fin de la chaîne.

```cpp
String System::String::TrimEnd(const String &anyOf) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) de caractères à supprimer. |

### Valeur de retour

[String](../) sans les caractères supprimés.

## String::TrimEnd(const ArrayPtr\<char_t\>\&) const méthode

Supprime toutes les occurrences des caractères passés à la fin de la chaîne.

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
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