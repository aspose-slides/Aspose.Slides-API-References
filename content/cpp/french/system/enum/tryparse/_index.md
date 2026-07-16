---
title: TryParse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Essaie de convertir la chaîne spécifiée en constante d'énumération équivalente.
type: docs
weight: 79
url: /fr/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) méthode

Essaie de convertir la chaîne spécifiée en constante d'énumération équivalente.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) that is interpreted as containing the name of enum constant |
| result | E\& | The output parameter that if conversion succeeds contains the result of conversion on function |

### Valeur de retour

True si la conversion a réussi, sinon - false

## Enum::TryParse(const String\&, bool, E\&) méthode

Essaie de convertir la chaîne spécifiée en constante d'énumération équivalente.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) that is interpreted as containing the name of enum constant |
| ignoreCase | **bool** | Specifies if the case should be ignored when interpreting the string |
| result | E\& | The output parameter that if conversion succeeds contains the result of conversion on function return |

### Valeur de retour

True si la conversion a réussi, sinon - false

## Voir aussi

* Classe [String](../../string/)
* Structure [Enum](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)