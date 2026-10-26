---
title: operator-()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce una nuova istanza della classe DateTimeOffset che rappresenta il valore di data e ora risultato della sottrazione dell'intervallo di tempo specificato dal valore rappresentato dall'oggetto corrente.
type: docs
weight: 521
url: /it/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const metodo

Restituisce una nuova istanza della classe [DateTimeOffset](../) che rappresenta il valore di data e ora risultato della sottrazione dell’intervallo di tempo specificato dal valore rappresentato dall’oggetto corrente.

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Un intervallo di tempo da sottrarre |

### Valore di ritorno

Una nuova istanza della classe [DateTimeOffset](../) che rappresenta il valore di data e ora risultato della sottrazione di **value** dal valore rappresentato dall’oggetto corrente.

## DateTimeOffset::operator-(const DateTimeOffset\&) const metodo

Restituisce un’istanza della classe [TimeSpan](../../timespan/) che rappresenta l’intervallo di tempo tra i valori di data e ora rappresentati dall’oggetto corrente e da quello specificato.

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | Un’istanza della classe [DateTime](../../datetime/) che segna un’estremità dell’intervallo da calcolare |

### Valore di ritorno

Un’istanza della classe [TimeSpan](../../timespan/) che rappresenta l’intervallo di tempo tra i valori di data e ora rappresentati dall’oggetto corrente e **other**.

## Vedi anche

* Classe [DateTimeOffset](../)
* Classe [TimeSpan](../../timespan/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)