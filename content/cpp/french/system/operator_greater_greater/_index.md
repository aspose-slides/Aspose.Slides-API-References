---
title: operator>>()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient une chaîne du flux d’entrée en utilisant l’encodage UTF-8.
type: docs
weight: 2965
url: /fr/system/operator_greater_greater/
---
## System::operator>>(std::istream\&, String\&) fonction


Obtient une chaîne du flux d’entrée en utilisant l’encodage UTF-8.

```cpp
std::istream & System::operator>>(std::istream &in, String &str)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| in | std::istream\& | Un objet flux d’entrée (instanciation de **basic_ostream** avec **char**). |
| str | [String](../string/)\& | Une chaîne à lire depuis le flux d’entrée. |

### Valeur de retour

Un flux d’entrée à partir duquel la chaîne a été extraite.

## System::operator>>(std::wistream\&, String\&) fonction


Obtient une chaîne du flux d’entrée.

```cpp
std::wistream & System::operator>>(std::wistream &in, String &str)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| in | std::wistream\& | Un objet flux d’entrée (instanciation de **basic_ostream** avec ****wchar_t****). |
| str | [String](../string/)\& | Une chaîne à lire depuis le flux d’entrée. |

### Valeur de retour

Un flux d’entrée à partir duquel la chaîne a été extraite.

## Voir aussi

* Classe [String](../string/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)