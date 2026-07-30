---
title: CompareOptions
second_title: Riferimento API di Aspose.Slides per C++
description: Opzioni di confronto delle stringhe.
type: docs
weight: 430
url: /it/system.globalization/compareoptions/
---
## CompareOptions enum


[String](../../system/string/) opzioni di confronto.

```cpp
enum class CompareOptions : int32_t
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | 0 | Nessuna opzione speciale. |
| IgnoreCase | 1 | Ignora le differenze di maiuscole/minuscole. |
| IgnoreNonSpace | 2 | Ignora i caratteri di combinazione non spaziatori, ad esempio i segni diacritici. |
| IgnoreSymbols | 4 | Include spazi bianchi, segni di punteggiatura e così via. |
| IgnoreKanaType | 8 | Ignora il tipo kana (giapponese). |
| IgnoreWidth | 16 | Ignora la larghezza dei caratteri quando si confrontano le stringhe. |
| OrdinalIgnoreCase | 268435456 | Confronto ordinale con differenza di maiuscole/minuscole ignorata. |
| StringSort | 536870912 | Utilizza l'algoritmo di ordinamento di stringhe per confrontare i caratteri. |
| Ordinal | 1073741824 | Confronta direttamente i codici UTF per il primo confronto. |

## Vedi anche

* Namespace [System::Globalization](../)
* Library [Aspose.Slides](../../)