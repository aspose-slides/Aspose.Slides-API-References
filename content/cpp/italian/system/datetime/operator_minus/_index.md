---
title: operator-()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce una nuova istanza della classe DateTime che rappresenta il valore di data e ora risultato della sottrazione dell'intervallo di tempo specificato dal valore rappresentato dall'oggetto corrente.
type: docs
weight: 651
url: /it/system/datetime/operator_minus/
---
## DateTime::operator-(TimeSpan) const metodo


Restituisce una nuova istanza della classe [DateTime](../) che rappresenta il valore di data e ora risultato della sottrazione dell'intervallo di tempo specificato dal valore rappresentato dall'oggetto corrente.

```cpp
DateTime System::DateTime::operator-(TimeSpan value) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Un intervallo di tempo da sottrarre |

### Valore restituito

Una nuova istanza della classe [DateTime](../) che rappresenta il valore di data e ora risultato della sottrazione di **value** dal valore rappresentato dall'oggetto corrente.

## DateTime::operator-(DateTime) const metodo


Restituisce un'istanza della classe [TimeSpan](../../timespan/) che rappresenta l'intervallo di tempo tra i valori di data e ora rappresentati dall'oggetto corrente e da quello specificato.

```cpp
constexpr TimeSpan System::DateTime::operator-(DateTime value) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DateTime](../) | Un'istanza della classe [DateTime](../) che segna un'estremità dell'intervallo da calcolare |

### Valore restituito

Un'istanza della classe [TimeSpan](../../timespan/) che rappresenta l'intervallo di tempo tra i valori di data e ora rappresentati dall'oggetto corrente e **value**.

## Vedi anche

* Classe [DateTime](../)
* Classe [TimeSpan](../../timespan/)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)