---
title: GetNumericValue()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la valeur numérique associée au caractère spécifié.
type: docs
weight: 27
url: /fr/system.globalization/charunicodeinfo/getnumericvalue/
---
## CharUnicodeInfo::GetNumericValue(char16_t) méthode


Obtient la valeur numérique associée au caractère spécifié.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(char16_t ch)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| ch | char16_t | Caractère Unicode. |

### Valeur de retour

La valeur numérique ou -1 si le caractère spécifié n’est pas un caractère numérique.

## CharUnicodeInfo::GetNumericValue(const String\&, int) méthode


Obtient la valeur numérique associée au caractère à l’indice spécifié de la chaîne.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(const String &str, int index)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | La chaîne contenant le caractère Unicode. |
| index | int | L’indice du caractère Unicode. |

### Valeur de retour

La valeur numérique ou -1 si le caractère spécifié n’est pas un caractère numérique.

## Voir aussi

* Classe [CharUnicodeInfo](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Globalization](../../)
* Bibliothèque [Aspose.Slides](../../../)