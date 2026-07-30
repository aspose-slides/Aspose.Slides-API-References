---
title: Size
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta una coppia di valori interi che indicano la larghezza e l'altezza di un'immagine. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire oggetti di questo tipo."
type: docs
weight: 274
url: /it/system.drawing/size/
---
## Classe Size

Rappresenta una coppia di valori interi che rappresentano la larghezza e l'altezza di un'immagine. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe [System::SmartPtr](../../system/smartptr/) per gestire oggetti di questo tipo.

```cpp
class Size
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static [Size](./) [Add](./add/)(const [Size](./)\&, const [Size](./)\&) | Restituisce un nuovo oggetto [Size](./) che è la somma dell'oggetto [Size](./) specificato, cioè il cui valore di larghezza è uguale alla somma dei valori di larghezza degli oggetti specificati e il valore di altezza è uguale alla somma dei valori di altezza degli oggetti specificati. |
| static [Size](./) [Ceiling](./ceiling/)(const [SizeF](../sizef/)\&) | Crea un oggetto [Size](./) dall'oggetto [SizeF](../sizef/) specificato arrotondando i valori di larghezza e altezza dell'oggetto [SizeF](../sizef/) al prossimo valore intero più alto. |
| **bool** [Equals](./equals/)(const [Size](./)\&) const | Determina se l'oggetto corrente e l'oggetto specificato sono uguali, cioè rappresentano la stessa coppia di valori di larghezza e altezza. |
| int [get_Height](./get_height/)() const | Restituisce il valore di altezza rappresentato dall'oggetto corrente. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determina se entrambi i valori di larghezza e altezza sono uguali a 0. |
| int [get_Width](./get_width/)() const | Restituisce il valore di larghezza rappresentato dall'oggetto corrente. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Restituisce un codice hash per l'oggetto corrente. |
| [operator Point](./operator_point/)() const | Crea un'istanza dell'oggetto [Point](../point/) e inizializza le sue coordinate X e Y con i valori di larghezza e altezza dell'oggetto corrente, rispettivamente. |
| [operator SizeF](./operator_sizef/)() const | Crea un'istanza dell'oggetto [SizeF](../sizef/) e la inizializza con i valori di larghezza e altezza dell'oggetto [Size](./) corrente. |
| static [Size](./) [Round](./round/)(const [SizeF](../sizef/)\&) | Crea un oggetto [Size](./) dall'oggetto [SizeF](../sizef/) specificato arrotondando i valori di larghezza e altezza dell'oggetto [SizeF](../sizef/) al valore intero più vicino. |
| void [set_Height](./set_height/)(int) | Imposta il valore di altezza rappresentato dall'oggetto corrente. |
| void [set_Width](./set_width/)(int) | Imposta il valore di larghezza rappresentato dall'oggetto corrente. |
| [Size](./size/)() | Crea un nuovo oggetto [Size](./) e inizializza i suoi valori di larghezza e altezza a 0. |
| [Size](./size/)(const [Point](../point/)\&) | Crea un nuovo oggetto [Size](./) e inizializza i suoi valori di larghezza e altezza con i valori delle coordinate X e Y del punto specificato, rispettivamente. |
| [Size](./size/)(int, int) | Crea un nuovo oggetto [Size](./) e lo inizializza con il valore specificato. |
| static [Size](./) [Subtract](./subtract/)(const [Size](./)\&, const [Size](./)\&) | Restituisce un nuovo oggetto [Size](./) che è il risultato della sottrazione di **size2** da **size1**, cioè il cui valore di larghezza è il risultato della sottrazione del valore di larghezza di **size2** dal valore di larghezza di **size1** e il valore di altezza è il risultato della sottrazione del valore di altezza di **size2** dal valore di altezza di **size1**. |
| [String](../../system/string/) [ToString](./tostring/)() const | Restituisce la rappresentazione stringa della coppia di valori di larghezza e altezza rappresentati dall'oggetto corrente. |
| static [Size](./) [Truncate](./truncate/)(const [SizeF](../sizef/)\&) | Crea un oggetto [Size](./) dall'oggetto [SizeF](../sizef/) specificato troncando i valori di larghezza e altezza dell'oggetto [SizeF](../sizef/) al prossimo valore intero inferiore. |

## Campi

| Campo | Descrizione |
| --- | --- |
| static [Empty](./empty/) | Un'istanza vuota della classe [Size](./) i cui valori di larghezza e altezza sono 0. |

## Vedi anche

* Namespace [System::Drawing](../)
* Libreria [Aspose.Slides](../../)