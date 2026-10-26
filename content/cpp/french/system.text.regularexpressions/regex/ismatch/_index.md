---
title: IsMatch()
second_title: Référence de l'API Aspose.Slides pour C++
description: Correspond l'expression régulière à la chaîne.
type: docs
weight: 53
url: /fr/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String&, int) méthode

Correspond à l'expression régulière dans la chaîne.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne cible. |
| startat | int | Index de début. |

### Valeur de retour

Vrai si la chaîne correspond à l'expression régulière, faux sinon.

## Regex::IsMatch(const String&, const String&, RegexOptions, TimeSpan, int) méthode

Vérifie si la chaîne correspond au motif.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne d'entrée. |
| pattern | const [String](../../../system/string/)\& | Modèle d'expression régulière. |
| options | [RegexOptions](../../regexoptions/) | Options de correspondance. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Délai d'attente. |
| startat | int | [Match](../../match/) position de début. |

### Valeur de retour

Vrai si une correspondance est trouvée, faux sinon.

## Voir aussi

* Enum [RegexOptions](../../regexoptions/)
* classe [String](../../../system/string/)
* classe [Regex](../)
* classe [TimeSpan](../../../system/timespan/)
* espace de noms [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)