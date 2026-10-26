---
title: SizeF
second_title: Riferimento API Aspose.Slides per C++
description: "Rappresenta una coppia di valori a virgola mobile a precisione singola che rappresentano la larghezza e l'altezza di un'immagine. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire oggetti di questo tipo."
type: docs
weight: 287
url: /it/system.drawing/sizef/
---
## SizeF classe


Rappresenta una coppia di valori a virgola mobile a precisione singola che rappresentano la larghezza e l'altezza di un'immagine. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe [System::SmartPtr](../../system/smartptr/) per gestire oggetti di questo tipo.

```cpp
class SizeF
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static [SizeF](./) [Add](./add/)(const [SizeF](./)\&, const [SizeF](./)\&) | Restituisce un nuovo oggetto [SizeF](./) che è la somma degli oggetti [SizeF](./) specificati, cioè il cui valore di larghezza è uguale alla somma dei valori di larghezza degli oggetti specificati e il valore di altezza è uguale alla somma dei valori di altezza degli oggetti specificati. |
| **bool** [Equals](./equals/)(const [SizeF](./)\&) const | Determina se l'oggetto corrente e l'oggetto specificato sono uguali, cioè rappresentano la stessa coppia di valori di larghezza e altezza. |
| **float** [get_Height](./get_height/)() const | Restituisce il valore di altezza rappresentato dall'oggetto corrente. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determina se entrambi i valori di larghezza e altezza sono uguali a 0. |
| **float** [get_Width](./get_width/)() const | Restituisce il valore di larghezza rappresentato dall'oggetto corrente. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Restituisce un codice hash per l'oggetto corrente. |
| [operator PointF](./operator_pointf/)() const | Converte l'oggetto corrente in un'istanza dell'oggetto [Point](../point/) inizializzando le sue coordinate X e Y con i valori di larghezza e altezza dell'oggetto corrente, rispettivamente. |
| [SizeF](./)\& [operator+=](./operator_plus_equal/)(const [SizeF](./)\&) | Aggiunge i valori di larghezza e altezza dell'oggetto [SizeF](./) specificato ai valori di larghezza e altezza dell'oggetto corrente [SizeF](./), rispettivamente. |
| void [set_Height](./set_height/)(**float**) | Imposta il valore di altezza rappresentato dall'oggetto corrente. |
| void [set_Width](./set_width/)(**float**) | Imposta il valore di larghezza rappresentato dall'oggetto corrente. |
| [SizeF](./sizef/)() | Costruisce un nuovo oggetto [SizeF](./) e inizializza i suoi valori di larghezza e altezza a 0. |
| [SizeF](./sizef/)(const [PointF](../pointf/)\&) | Costruisce un nuovo oggetto [SizeF](./) e inizializza i suoi valori di larghezza e altezza con i valori delle coordinate X e Y del punto specificato, rispettivamente. |
| [SizeF](./sizef/)(**float**, **float**) | Costruisce un nuovo oggetto [SizeF](./) e lo inizializza con il valore specificato. |
| static [SizeF](./) [Subtract](./subtract/)(const [SizeF](./)\&, const [SizeF](./)\&) | Restituisce un nuovo oggetto [SizeF](./) che è il risultato della sottrazione di **size2** da **size1**, cioè il cui valore di larghezza è il risultato della sottrazione del valore di larghezza di **size2** dal valore di larghezza di **size1** e il valore di altezza è il risultato della sottrazione del valore di altezza di **size2** dal valore di altezza di **size1**. |
| [PointF](../pointf/) [ToPointF](./topointf/)() const | Converte l'oggetto corrente in un'istanza dell'oggetto [Point](../point/) inizializzando le sue coordinate X e Y con i valori di larghezza e altezza dell'oggetto corrente, rispettivamente. |
| [Size](../size/) [ToSize](./tosize/)() const | Costruisce un oggetto [Size](../size/) dall'oggetto corrente [SizeF](./) troncando i valori di larghezza e altezza dell'oggetto [SizeF](./) al valore intero inferiore più vicino. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Restituisce la rappresentazione stringa della coppia di valori di larghezza e altezza rappresentati dall'oggetto corrente. |

## Campi

| Campo | Descrizione |
| --- | --- |
| static [Empty](./empty/) | Un'istanza vuota della classe [SizeF](./) i cui valori di larghezza e altezza sono 0. |

## Vedi anche

* Spazio dei nomi [System::Drawing](../)
* Libreria [Aspose.Slides](../../)