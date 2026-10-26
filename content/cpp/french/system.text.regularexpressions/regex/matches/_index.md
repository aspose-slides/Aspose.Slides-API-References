---
title: Matches()
second_title: Référence API Aspose.Slides pour C++
description: Obtient toutes les correspondances de l'expression régulière dans la chaîne donnée en effectuant des correspondances répétées.
type: docs
weight: 79
url: /fr/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) méthode

Obtient toutes les correspondances de l'expression régulière dans la chaîne donnée en effectuant des correspondances répétées.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne d'entrée. |
| startat | int | Index à partir duquel commencer la correspondance. |

### Valeur de retour

Collection de toutes les correspondances trouvées.

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) méthode

Obtient toutes les correspondances entre la chaîne et le modèle.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne d'entrée. |
| pattern | const [String](../../../system/string/)\& | Modèle d'expression régulière. |
| options | [RegexOptions](../../regexoptions/) | Options de correspondance. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Délai d'attente. |
| startat | int | [Match](../../match/) position de départ. |
| length | int | Nombre de caractères à parcourir (0 désactive la limite). |

### Valeur de retour

Toutes les correspondances trouvées en effectuant des correspondances répétées.

## Voir aussi

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Classe [String](../../../system/string/)
* Classe [Regex](../)
* Classe [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)