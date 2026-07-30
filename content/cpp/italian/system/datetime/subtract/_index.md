---
title: Subtract()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce una nuova istanza della classe DateTime che rappresenta il valore di data e ora risultato della sottrazione dell'intervallo di tempo specificato dal valore rappresentato dall'oggetto corrente.
type: docs
weight: 326
url: /it/system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const metodo

Restituisce una nuova istanza della classe [DateTime](../) che rappresenta il valore di data e ora risultato della sottrazione dell'intervallo di tempo specificato dal valore rappresentato dall'oggetto corrente.

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | Un intervallo di tempo da sottrarre |

### Valore di ritorno

Una nuova istanza della classe [DateTime](../) che rappresenta il valore di data e ora risultato della sottrazione di **duration** dal valore rappresentato dall'oggetto corrente.

## DateTime::Subtract(DateTime) const metodo

Restituisce un'istanza della classe [TimeSpan](../../timespan/) che rappresenta l'intervallo di tempo tra i valori di data e ora rappresentati dall'oggetto corrente e da quello specificato.

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DateTime](../) | Un'istanza della classe [DateTime](../) che segna un'estremità dell'intervallo da calcolare |

### Valore di ritorno

Un'istanza della classe [TimeSpan](../../timespan/) che rappresenta l'intervallo di tempo tra i valori di data e ora rappresentati dall'oggetto corrente e da **value**.

## Vedi anche

* Classe [DateTime](../)
* Classe [TimeSpan](../../timespan/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)