---
title: ConvertToUtf32()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la paire de substitution UTF-16 spécifiée en unité de code UTF-32.
type: docs
weight: 287
url: /fr/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) méthode


Convertit la paire de substitution UTF-16 spécifiée en unité de code UTF-32.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| highSurrogate | char_t | Le substitut haut de la paire de substitution UTF-16 à convertir |
| lowSurrogate | char_t | Le substitut bas de la paire de substitution UTF-16 à convertir |

### Return Value

Une unité de code UTF-32 résultant de la conversion

## Char::ConvertToUtf32(const String\&, int) méthode


Convertit la valeur d'un caractère ou d'une paire de substitution encodé en UTF-16 à une position spécifiée dans une chaîne en unité de code UTF-32.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | Une chaîne qui contient un caractère ou une paire de substitution |
| index | int | La position d'index du caractère ou de la paire de substitution dans la chaîne spécifiée |

### Return Value

Une unité de code UTF-32 résultant de la conversion

## Voir aussi

* Classe [Char](../)
* Classe [String](../../string/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)