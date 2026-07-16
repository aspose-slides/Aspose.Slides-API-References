---
title: IsHighSurrogate()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si le caractère à l'index spécifié dans la chaîne spécifiée est une unité de code haute substitution UTF-16.
type: docs
weight: 40
url: /fr/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) méthode

Détermine si le caractère à l'index spécifié dans la chaîne spécifiée est une unité de code haute substitution UTF-16.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | Une chaîne |
| index | int | L'index dans la chaîne spécifiée du caractère à tester |

### Valeur de retour

true si le caractère à l'index spécifié est une unité de code haute substitution UTF-16, sinon - false

## Char::IsHighSurrogate(const char_t *, int) méthode

Détermine si le caractère à l'index spécifié dans le tampon de caractères spécifié est un haut substituant.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const char_t * | Pointeur vers le début du tampon de caractères |
| idx | int | Un indice basé sur zéro dans le tampon spécifié du caractère à tester |

### Valeur de retour

true si le caractère à l'index spécifié est un haut substituant, sinon - false

## Char::IsHighSurrogate(char_t) méthode

Détermine si le caractère spécifié est un haut substituant.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| c | char_t | Le caractère à tester |

### Valeur de retour

true si le caractère spécifié est un haut substituant, sinon - false

## Voir aussi

* Classe [String](../../string/)
* Classe [Char](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)