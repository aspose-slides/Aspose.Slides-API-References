---
title: Point
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta una coppia di coordinate intere X e Y di un punto su un piano bidimensionale. Questo tipo dovrebbe essere allocato nello stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire oggetti di questo tipo."
type: docs
weight: 209
url: /it/system.drawing/point/
---
## Point classe

Represents a pair of integer X and Y coordinates of a point on a 2-dimensional plane. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) classe to manage objects of this type.

```cpp
class Point
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static [Point](./) [Add](./add/)(const [Point](./)\&, const [Size](../size/)\&) | Aggiunge i valori di larghezza e altezza dell'oggetto [Size](../size/) specificato ai valori delle coordinate X e Y dell'oggetto [Point](./) specificato corrispondentemente. |
| static [Point](./) [Ceiling](./ceiling/)(const [PointF](../pointf/)\&) | Costruisce un oggetto [Point](./) dall'oggetto [PointF](../pointf/) specificato arrotondando i valori delle coordinate X e Y dell'oggetto [PointF](../pointf/) al prossimo valore intero superiore. |
| **bool** [Equals](./equals/)(const [Point](./)\&) const | Determina se l'oggetto corrente e l'oggetto specificato sono uguali, cioè rappresentano la stessa coppia di valori delle coordinate X e Y. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determina se entrambi i valori delle coordinate X e Y sono uguali a 0. |
| int [get_X](./get_x/)() const | Restituisce il valore della coordinata X rappresentato dall'oggetto corrente. |
| int [get_Y](./get_y/)() const | Restituisce il valore della coordinata Y rappresentato dall'oggetto corrente. |
| int [GetHashCode](./gethashcode/)() const | Restituisce un codice hash per l'oggetto corrente. |
| size_t [getStdHash](./getstdhash/)() const | Restituisce un valore hash per l'oggetto corrente. |
| **bool** [IsNull](./isnull/)() const | Restituisce sempre false. |
| void [Offset](./offset/)(int, int) | Sposta il valore delle coordinate X e Y rappresentato dall'oggetto corrente dei valori specificati. |
| void [Offset](./offset/)([Point](./)) | Sposta le coordinate X e Y rappresentate dall'oggetto corrente dei valori delle coordinate X e Y rappresentate dall'oggetto [Point](./) specificato corrispondentemente. |
|  [operator PointF](./operator_pointf/)() const | Costruisce un'istanza dell'oggetto [PointF](../pointf/) e la inizializza con i valori delle coordinate X e Y dell'oggetto [Point](./) corrente. |
|  [operator Size](./operator_size/)() const | Costruisce un'istanza dell'oggetto [Size](../size/) e inizializza i suoi valori di larghezza e altezza con i valori delle coordinate X e Y rappresentati dall'oggetto corrente corrispondentemente. |
|  [Point](./point/)() | Costruisce un nuovo oggetto [Point](./) e inizializza i suoi valori delle coordinate X e Y a 0. |
|  [Point](./point/)(int, int) | Costruisce un nuovo oggetto [Point](./) e lo inizializza con i valori specificati. |
|  [Point](./point/)(const [Size](../size/)\&) | Costruisce un nuovo oggetto [Point](./) e inizializza i suoi valori delle coordinate X e Y con i valori di larghezza e altezza dell'oggetto [SizeF](../sizef/) specificato corrispondentemente. |
|  [Point](./point/)(int) | Costruisce un nuovo oggetto [Point](./) e inizializza il valore della coordinata X con un valore formato dai 16 bit più alti del intero a 32 bit specificato e il valore della coordinata Y con un valore formato dai 16 bit più bassi del intero a 32 bit specificato. |
| static [Point](./) [Round](./round/)(const [PointF](../pointf/)\&) | Costruisce un oggetto [Point](./) dall'oggetto [PointF](../pointf/) specificato arrotondando i valori delle coordinate X e Y dell'oggetto [PointF](../pointf/) al valore intero più vicino. |
| void [set_X](./set_x/)(int) | Imposta il valore della coordinata X rappresentata dall'oggetto corrente. |
| void [set_Y](./set_y/)(int) | Imposta il valore della coordinata Y rappresentata dall'oggetto corrente. |
| static [Point](./) [Subtract](./subtract/)(const [Point](./)\&, const [Size](../size/)\&) | Sottrae i valori di larghezza e altezza dell'oggetto [Size](../size/) specificato dai valori delle coordinate X e Y dell'oggetto [Point](./) specificato corrispondentemente. |
| [String](../../system/string/) [ToString](./tostring/)() const | Restituisce la rappresentazione stringa della coppia di valori delle coordinate X e Y rappresentata dall'oggetto corrente. |
| static [Point](./) [Truncate](./truncate/)(const [PointF](../pointf/)\&) | Costruisce un oggetto [Point](./) dall'oggetto [PointF](../pointf/) specificato troncando i valori delle coordinate X e Y dell'oggetto [PointF](../pointf/) al prossimo valore intero inferiore. |

## Campi

| Campo | Descrizione |
| --- | --- |
| static [Empty](./empty/) | Un'istanza vuota della classe [Point](./) i cui valori delle coordinate X e Y sono 0. |

## Vedi anche

* Spazio dei nomi [System::Drawing](../)
* Libreria [Aspose.Slides](../../)