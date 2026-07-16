---
title: Split()
second_title: Référence de l'API Aspose.Slides pour C++
description: Divise la chaîne selon les correspondances d'expression régulière.
type: docs
weight: 105
url: /fr/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) méthode


Divise la chaîne selon les correspondances d'expression régulière.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) à diviser. |

### Valeur de retour

[Array](../../../system/array/) de sous-chaînes entre les correspondances.

## Regex::Split(const String\&, int) méthode


Divise la chaîne selon les correspondances d'expression régulière.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) à diviser. |
| count | int | Limite du nombre de sous-chaînes. |

### Valeur de retour

[Array](../../../system/array/) de sous-chaînes entre les correspondances.

## Regex::Split(const String\&, int, int) méthode


Divise une chaîne d'entrée un nombre maximal de fois spécifié en un tableau de sous-chaînes, aux positions définies par une expression régulière spécifiée dans le constructeur [Regex](../). La recherche du motif d'expression régulière commence à une position de caractère spécifiée dans la chaîne d'entrée.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | La chaîne à diviser. |
| count | int | Le nombre maximal de divisions. |
| startat | int | La position du caractère dans la chaîne d'entrée où la recherche commencera. |

### Valeur de retour

Un tableau de chaînes.

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) méthode


Divise la chaîne selon l'expression régulière.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne d'entrée. |
| pattern | const [String](../../../system/string/)\& | Motif d'expression régulière. |
| options | [RegexOptions](../../regexoptions/) | Options de correspondance. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Délai d'expiration. |

### Valeur de retour

[Array](../../../system/array/) de chaînes entre les correspondances.

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) méthode


Divise la chaîne selon l'expression régulière.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne d'entrée. |
| pattern | const [String](../../../system/string/)\& | Motif d'expression régulière. |
| count | int | [Match](../../match/) limite du nombre. |
| options | [RegexOptions](../../regexoptions/) | Options de correspondance. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Délai d'expiration. |

### Valeur de retour

[Array](../../../system/array/) de chaînes entre les correspondances.

## Voir aussi

* Enum [RegexOptions](../../regexoptions/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)