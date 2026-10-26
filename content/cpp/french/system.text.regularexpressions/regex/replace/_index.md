---
title: Replace()
second_title: Référence API Aspose.Slides pour C++
description: Remplace toutes les correspondances de l'expression régulière dans la chaîne par la chaîne de remplacement.
type: docs
weight: 92
url: /fr/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String&, const String&) méthode


Remplace toutes les correspondances de l’expression régulière dans la chaîne par la chaîne de remplacement.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne d’entrée. |
| replacement | const [String](../../../system/string/)\& | Chaîne de remplacement. |

### Valeur de retour

Chaîne d’entrée avec toutes les correspondances de l’expression régulière remplacées par la chaîne de remplacement.

## Regex::Replace(const String&, const char_t *) méthode


Remplace toutes les correspondances de l’expression régulière dans la chaîne par la chaîne de remplacement.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne d’entrée. |
| replacement | const char_t * | Chaîne de remplacement. |

### Valeur de retour

Chaîne d’entrée avec toutes les correspondances de l’expression régulière remplacées par la chaîne de remplacement.

## Regex::Replace(const String&, const MatchEvaluator&) méthode


Remplace toutes les correspondances dans la chaîne par des chaînes de remplacement générées par le délégué.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne d’entrée. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Délégué pour générer des chaînes de remplacement à partir des correspondances. |

### Valeur de retour

Chaînes d’entrée avec toutes les correspondances remplacées.

## Regex::Replace(const String&, const MatchEvaluator&, int) méthode


Remplace toutes les correspondances dans la chaîne par des chaînes de remplacement générées par le délégué.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne d’entrée. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Délégué pour générer des chaînes de remplacement à partir des correspondances. |
| count | int | Limite du nombre de remplacements. |

### Valeur de retour

Chaînes d’entrée avec toutes les correspondances remplacées.

## Regex::Replace(const String&, const MatchEvaluator&, int, int) méthode


Remplace toutes les correspondances dans la chaîne par des chaînes de remplacement générées par le délégué.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne d’entrée. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Délégué pour générer des chaînes de remplacement à partir des correspondances. |
| count | int | Limite du nombre de remplacements. |
| startat | int | Indice dans la chaîne d’entrée où commencer le remplacement. |

### Valeur de retour

Chaînes d’entrée avec toutes les correspondances remplacées.

## Regex::Replace(const String&, const String&, int) méthode


Remplace des sous-chaînes dans la chaîne. Non implémenté.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String&, const String&, int, int) méthode


Remplace des sous-chaînes dans la chaîne. Non implémenté.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String&, const char_t *, const char_t *) méthode


Remplace toutes les correspondances de l’expression régulière dans la chaîne par la chaîne de remplacement.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne d’entrée. |
| pattern | const char_t * | [Regex](../) modèle. |
| replacement | const char_t * | Chaîne de remplacement. |

### Valeur de retour

Chaîne d’entrée avec toutes les correspondances de l’expression régulière remplacées par la chaîne de remplacement.

## Regex::Replace(const String&, const String&, const char_t *) méthode


Remplace toutes les correspondances de l’expression régulière dans la chaîne par la chaîne de remplacement.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne d’entrée. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) modèle. |
| replacement | const char_t * | Chaîne de remplacement. |

### Valeur de retour

Chaîne d’entrée avec toutes les correspondances de l’expression régulière remplacées par la chaîne de remplacement.

## Regex::Replace(const String&, const String&, const MatchEvaluator&, RegexOptions) méthode


Remplace toutes les correspondances dans la chaîne par des chaînes de remplacement générées par le délégué (fonction statique).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne d’entrée. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) modèle. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Délégué pour générer des chaînes de remplacement à partir des correspondances. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) options. |

### Valeur de retour

Chaînes d’entrée avec toutes les correspondances remplacées.

## Regex::Replace(const String&, const String&, const String&, RegexOptions) méthode


Remplace toutes les correspondances de l’expression régulière dans la chaîne par la chaîne de remplacement.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne d’entrée. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) modèle. |
| replacement | const [String](../../../system/string/)\& | Chaîne de remplacement. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) options. |

### Valeur de retour

Chaîne d’entrée avec toutes les correspondances de l’expression régulière remplacées par la chaîne de remplacement.

## Regex::Replace(const String&, const String&, const String&) méthode


Remplace les correspondances de l’expression régulière.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne d’entrée. |
| pattern | const [String](../../../system/string/)\& | Motif Regexp. |
| replacement | const [String](../../../system/string/)\& | Chaîne de remplacement. |

### Valeur de retour

[String](../../../system/string/) avec toutes les correspondances remplacées.

## Regex::Replace(const String&, const String&, const MatchEvaluator&) méthode


Remplace les correspondances de l’expression régulière.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Chaîne d’entrée. |
| pattern | const [String](../../../system/string/)\& | Motif Regexp. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Délégué pour générer une chaîne de remplacement pour chaque correspondance. |

### Valeur de retour

[String](../../../system/string/) avec toutes les correspondances remplacées.

## Voir aussi

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Classe [String](../../../system/string/)
* Classe [Regex](../)
* Espace de noms [System::Text::RegularExpressions](../../)
* Bibliothèque [Aspose.Slides](../../../)