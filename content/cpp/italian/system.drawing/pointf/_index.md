---
title: PointF
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta una coppia di coordinate X e Y a virgola mobile a precisione singola di un punto su un piano bidimensionale. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire oggetti di questo tipo."
type: docs
weight: 222
url: /it/system.drawing/pointf/
---
## PointF classe

Rappresenta una coppia di coordinate X e Y a virgola mobile a precisione singola di un punto su un piano bidimensionale. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe [System::SmartPtr](../../system/smartptr/) per gestire oggetti di questo tipo.

```cpp
class PointF
```

## Metodi

| Method | Description |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Aggiunge i valori di larghezza e altezza dell'oggetto [SizeF](../sizef/) specificato ai valori delle coordinate X e Y dell'oggetto [PointF](./) specificato corrispondentemente. |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | Aggiunge i valori di larghezza e altezza dell'oggetto [Size](../size/) specificato ai valori delle coordinate X e Y dell'oggetto [PointF](./) specificato corrispondentemente. |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | Determina se l'oggetto corrente e l'oggetto specificato sono uguali, cioè rappresentano la stessa coppia di valori di coordinate X e Y. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determina se i valori delle coordinate X e Y sono entrambi uguali a 0. |
| **float** [get_X](./get_x/)() const | Restituisce il valore della coordinata X rappresentato dall'oggetto corrente. |
| **float** [get_Y](./get_y/)() const | Restituisce il valore della coordinata Y rappresentato dall'oggetto corrente. |
| int [GetHashCode](./gethashcode/)() const | Restituisce un codice hash per l'oggetto corrente. |
| **bool** [IsNull](./isnull/)() const | Restituisce sempre false. |
| explicit  [operator bool](./operator_bool/)() | Restituisce sempre true. |
|  [PointF](./pointf/)() | Crea un nuovo oggetto [PointF](./) e inizializza i suoi valori di coordinate X e Y a 0. |
|  [PointF](./pointf/)(**float**, **float**) | Crea un nuovo oggetto [PointF](./) e lo inizializza con i valori specificati. |
|  [PointF](./pointf/)(const [SizeF](../sizef/)\&) | Crea un nuovo oggetto [PointF](./) e inizializza i suoi valori di coordinate X e Y con i valori di larghezza e altezza dell'oggetto [SizeF](../sizef/) specificato corrispondentemente. |
| void [set_X](./set_x/)(**float**) | Imposta il valore della coordinata X rappresentata dall'oggetto corrente. |
| void [set_Y](./set_y/)(**float**) | Imposta il valore della coordinata Y rappresentata dall'oggetto corrente. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Sottrae i valori di larghezza e altezza dell'oggetto [SizeF](../sizef/) specificato dai valori delle coordinate X e Y dell'oggetto [PointF](./) specificato corrispondentemente. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | Sottrae i valori di larghezza e altezza dell'oggetto [Size](../size/) specificato dai valori delle coordinate X e Y dell'oggetto [PointF](./) specificato corrispondentemente. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Restituisce la rappresentazione testuale della coppia di valori di coordinate X e Y rappresentata dall'oggetto corrente. |

## Campi

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Un'istanza vuota della classe [PointF](./) i cui valori di coordinate X e Y sono 0. |

## Vedi anche

* Namespace [System::Drawing](../)
* Libreria [Aspose.Slides](../../)