---
title: Match()
second_title: Référence de l'API Aspose.Slides pour C++
description: Correspond à l'expression régulière sur la chaîne.
type: docs
weight: 66
url: /fr/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) méthode


Correspond à l’expression régulière sur la chaîne.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne cible. |

### Return Value

[Match](../../match/) valeur contenant le statut de la correspondance et les sous-correspondances.

## Regex::Match(const String\&, int, int) méthode


Correspond à l’expression régulière sur la chaîne.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne cible. |
| startat | int | Indice de début. |
| length | int | Nombre de caractères à parcourir (0 pour parcourir la chaîne entière). |

### Return Value

[Match](../../match/) valeur contenant le statut de la correspondance et les sous-correspondances.

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) méthode


Correspond à la chaîne et au motif.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne d'entrée. |
| pattern | const [String](../../../system/string/)\& | Motif d'expression régulière. |
| options | [RegexOptions](../../regexoptions/) | Options de correspondance. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Délai d'attente. |
| startat | int | [Match](../../match/) position de début. |
| length | int | Nombre de caractères à parcourir (0 désactive la limite). |

### Return Value

Première correspondance trouvée.

## See Also

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)