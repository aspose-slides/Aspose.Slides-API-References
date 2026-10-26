---
title: IsMatch()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica la corrispondenza della regex con la stringa.
type: docs
weight: 53
url: /it/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) metodo

Verifica la corrispondenza della regex con la stringa.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di input. |
| startat | int | Indice iniziale. |

### Valore restituito

true se la stringa corrisponde alla regex, false altrimenti.

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) metodo

Verifica se la stringa corrisponde al modello.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Stringa di input. |
| pattern | const [String](../../../system/string/)\& | Modello regex. |
| options | [RegexOptions](../../regexoptions/) | Opzioni di corrispondenza. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Timeout. |
| startat | int | [Match](../../match/) posizione iniziale. |

### Valore restituito

true se la corrispondenza è trovata, false altrimenti.

## Vedi anche

* Enum [RegexOptions](../../regexoptions/)
* Classe [String](../../../system/string/)
* Classe [Regex](../)
* Classe [TimeSpan](../../../system/timespan/)
* Spazio dei nomi [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)