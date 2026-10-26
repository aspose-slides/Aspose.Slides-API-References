---
title: Equals< float, float >()
second_title: Riferimento API di Aspose.Slides per C++
description: "Specializzazione per valori in virgola mobile a precisione singola. Sebbene due NaN a virgola mobile siano definiti dallo IEC 60559:1989 per essere sempre confrontati come disuguali, il contratto per System.Object.Equals richiede che le sovrascritture soddisfino i requisiti per un operatore di equivalenza. Pertanto, System.Double.Equals e System.Single.Equals restituiscono True quando confrontano due NaN, mentre l'operatore di uguaglianza restituisce False in quel caso, come richiesto dallo standard."
type: docs
weight: 2705
url: /it/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) funzione


Specializzazione per valori in virgola mobile a precisione singola. Sebbene due NaN in virgola mobile siano definiti dallo IEC 60559:1989 per essere sempre confrontati come disuguali, il contratto per [System.Object.Equals](../object/equals/) richiede che le sovrascritture soddisfino i requisiti per un operatore di equivalenza. Pertanto, System.Double.Equals e System.Single.Equals restituiscono True quando confrontano due NaN, mentre l'operatore di uguaglianza restituisce False in quel caso, come richiesto dallo standard.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | const **float**\& | Il primo comparando |
| b | const **float**\& | Il secondo comparando |

### Valore di ritorno

True se entrambi i valori sono NaN o sono uguali, altrimenti - false

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)