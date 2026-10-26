---
title: RegexOptions
second_title: Riferimento API di Aspose.Slides per C++
description: Opzioni regex.
type: docs
weight: 118
url: /it/system.text.regularexpressions/regexoptions/
---
## RegexOptions enum

[Regex](../regex/) opzioni.

```cpp
enum class RegexOptions
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | 0 | Comportamento predefinito. |
| Compiled | 1 | Compila regex per le prestazioni. Sempre eseguito per impostazione predefinita. |
| CultureInvariant | 2 | Usa corrispondenza indipendente dalla cultura. Ignorato. |
| ECMAScript | 4 | Usa sintassi ECMAScript. Ignorato. |
| ExplicitCapture | 8 | Solo cattura esplicita. Ignorato. |
| IgnoreCase | 16 | Ignora il maiuscolo/minuscolo durante la corrispondenza. |
| IgnorePatternWhitespace | 32 | Ignora spazi bianchi nel pattern. Non supportato. |
| Multiline | 64 | Considera '^' e '$' come inizio e fine riga, non dell'intera stringa. |
| RightToLeft | 128 | Corrispondenza da destra a sinistra. Non supportato. |
| Singleline | 256 | Fa sì che '.' corrisponda a qualsiasi carattere senza eccezioni (normalmente i caratteri di nuova riga non sono corrisposti). |

## Vedi anche

* Spazio dei nomi [System::Text::RegularExpressions](../)
* Libreria [Aspose.Slides](../../)