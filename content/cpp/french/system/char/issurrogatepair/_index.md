---
title: IsSurrogatePair()
second_title: Référence API Aspose.Slides for C++
description: Détermine si les deux caractères spécifiés forment une paire de substituts UTF-16.
type: docs
weight: 27
url: /fr/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) méthode

Détermine si les deux caractères spécifiés forment une paire de substituts UTF-16.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| highSurrogate | char_t | Un caractère testé pour être un substitut haut |
| lowSurrogate | char_t | Un caractère testé pour être un substitut bas |

### Valeur de retour

Vrai si les caractères spécifiés forment une paire de substituts, sinon - faux

## Char::IsSurrogatePair(const String\\&, int) méthode

Détermine si deux caractères consécutifs dans le tampon de caractères spécifié constituent une paire de substituts.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | Une chaîne |
| index | int | Un indice basé sur zéro dans le tampon spécifié où commence la séquence de caractères à tester |

### Valeur de retour

Vrai si les caractères spécifiés forment une paire de substituts, sinon - faux

## Voir aussi

* Classe [Char](../)
* Classe [String](../../string/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)