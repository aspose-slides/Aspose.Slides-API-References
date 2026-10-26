---
title: Match()
second_title: Riferimento API Aspose.Slides per C++
description: Esegue il match della regex sulla stringa.
type: docs
weight: 66
url: /it/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) metodo

Esegue il match della regex sulla stringa.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di destinazione. |

### Valore restituito

[Match](../../match/) valore contenente lo stato del match e le sottocorrispondenze.

## Regex::Match(const String\&, int, int) metodo

Esegue il match della regex sulla stringa.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di destinazione. |
| startat | int | Indice iniziale. |
| length | int | Numero di caratteri da analizzare (0 per analizzare l'intera stringa). |

### Valore restituito

[Match](../../match/) valore contenente lo stato del match e le sottocorrispondenze.

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) metodo

Esegue il match della stringa e del modello.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di input. |
| pattern | const [String](../../../system/string/)\& | Modello Regexp. |
| options | [RegexOptions](../../regexoptions/) | Opzioni di matching. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Timeout. |
| startat | int | [Match](../../match/) posizione iniziale. |
| length | int | Numero di caratteri da analizzare (0 disabilita il limite). |

### Valore restituito

Primo match trovato.

## Vedi anche

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)