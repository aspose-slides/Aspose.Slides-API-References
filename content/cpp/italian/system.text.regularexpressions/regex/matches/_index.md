---
title: Matches()
second_title: Riferimento API Aspose.Slides per C++
description: Ottiene tutte le corrispondenze della regex nella stringa fornita eseguendo confronti ripetuti.
type: docs
weight: 79
url: /it/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) method


Ottiene tutte le corrispondenze della regex nella stringa fornita eseguendo confronti ripetuti.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di input. |
| startat | int | [Index](../../../system/index/) per iniziare il confronto a. |

### Valore di ritorno

Collezione di tutti i risultati trovati.

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) method


Ottiene tutte le corrispondenze tra la stringa e il modello.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di input. |
| pattern | const [String](../../../system/string/)\& | Modello regexp. |
| options | [RegexOptions](../../regexoptions/) | Opzioni di confronto. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Timeout. |
| startat | int | [Match](../../match/) posizione iniziale. |
| length | int | Numero di caratteri da esaminare (0 disabilita il limite). |

### Valore di ritorno

Tutti i risultati trovati mediante confronti ripetuti.

## Vedi anche

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)