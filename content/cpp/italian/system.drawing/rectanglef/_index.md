---
title: RectangleF
second_title: Riferimento API Aspose.Slides per C++
description: "Rappresenta un'area rettangolare di un'immagine definita come coordinate X e Y a precisione singola in virgola mobile dell'angolo superiore sinistro e la sua larghezza e altezza. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire gli oggetti di questo tipo."
type: docs
weight: 248
url: /it/system.drawing/rectanglef/
---
## RectangleF classe

Rappresenta un'area rettangolare di un'immagine definita come coordinate X e Y a precisione singola in virgola mobile dell'angolo superiore sinistro e la sua larghezza e altezza. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe [System::SmartPtr](../../system/smartptr/) per gestire gli oggetti di questo tipo.

```cpp
class RectangleF
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | Determina se il punto specificato si trova all'interno del rettangolo rappresentato dall'oggetto corrente. |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | Determina se il punto specificato si trova all'interno del rettangolo rappresentato dall'oggetto corrente. |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | Determina se il rettangolo specificato si trova all'interno del rettangolo rappresentato dall'oggetto corrente. |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | Determina se i rettangoli rappresentati dall'oggetto corrente e da quello specificato sono identici. |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | Crea un nuovo oggetto [RectangleF](./) che rappresenta un rettangolo con le posizioni dei bordi specificate. |
| **float** [get_Bottom](./get_bottom/)() const | Restituisce la coordinata y del bordo inferiore del rettangolo rappresentato dall'oggetto corrente. |
| **float** [get_Height](./get_height/)() const | Restituisce l'altezza del rettangolo rappresentato dall'oggetto corrente. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determina se le coordinate X e Y dell'angolo superiore sinistro del rettangolo rappresentato dall'oggetto corrente, così come la sua larghezza e altezza, hanno valore 0. |
| **float** [get_Left](./get_left/)() const | Restituisce la coordinata X del bordo sinistro del rettangolo rappresentato dall'oggetto corrente. |
| [PointF](../pointf/) [get_Location](./get_location/)() const | Restituisce un'istanza della classe [PointF](../pointf/) che specifica la posizione dell'angolo superiore sinistro del rettangolo rappresentato dall'oggetto corrente. |
| **float** [get_Right](./get_right/)() const | Restituisce la coordinata X del bordo destro del rettangolo rappresentato dall'oggetto corrente. |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | Restituisce un'istanza della classe [SizeF](../sizef/) che specifica la larghezza e l'altezza del rettangolo rappresentato dall'oggetto corrente. |
| **float** [get_Top](./get_top/)() const | Restituisce la coordinata Y del bordo superiore del rettangolo rappresentato dall'oggetto corrente. |
| **float** [get_Width](./get_width/)() const | Restituisce la larghezza del rettangolo rappresentato dall'oggetto corrente. |
| **float** [get_X](./get_x/)() const | Restituisce la coordinata X dell'angolo superiore sinistro del rettangolo rappresentato dall'oggetto corrente. |
| **float** [get_Y](./get_y/)() const | Restituisce la coordinata Y dell'angolo superiore sinistro del rettangolo rappresentato dall'oggetto corrente. |
| int [GetHashCode](./gethashcode/)() const | Restituisce un codice hash dell'oggetto corrente. |
| void [Inflate](./inflate/)(**float**, **float**) | Aumenta la larghezza e l'altezza del rettangolo rappresentato dall'oggetto corrente, mantenendo la posizione del centro geometrico del rettangolo. La larghezza e l'altezza sono aumentate in entrambe le direzioni degli importi specificati. |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | Aumenta la larghezza e l'altezza del rettangolo rappresentato dall'oggetto corrente, mantenendo la posizione del centro geometrico del rettangolo. La larghezza e l'altezza sono aumentate in entrambe le direzioni dei valori di larghezza e altezza dell'oggetto size specificato corrispondentemente. |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | Aumenta la larghezza e l'altezza del rettangolo rappresentato dall'oggetto specificato, mantenendo la posizione del centro geometrico del rettangolo. La larghezza e l'altezza sono aumentate in entrambe le direzioni degli importi specificati. |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | Sostituisce il rettangolo rappresentato dall'oggetto corrente con il rettangolo risultante dalla sua intersezione con il rettangolo rappresentato dall'oggetto specificato. |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Restituisce un rettangolo che è il risultato dell'intersezione dei rettangoli specificati. |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | Determina se i rettangoli rappresentati dall'oggetto corrente e da quello specificato si intersecano. |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | Sposta la posizione del rettangolo rappresentato dall'oggetto corrente degli importi specificati. |
| void [Offset](./offset/)(**float**, **float**) | Sposta la posizione del rettangolo rappresentato dall'oggetto corrente degli importi specificati. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Restituisce sempre true. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Restituisce sempre false. |
|  [RectangleF](./rectanglef/)() | Crea una nuova istanza dell'oggetto [RectangleF](./) che rappresenta un rettangolo con coordinate X e Y e valori di larghezza e altezza impostati a 0. |
|  [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | Crea una nuova istanza dell'oggetto [RectangleF](./) che rappresenta un rettangolo con le coordinate specificate dell'angolo superiore sinistro e larghezza e altezza. |
|  [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | Crea una nuova istanza dell'oggetto [RectangleF](./) che rappresenta un rettangolo con le coordinate del suo angolo superiore sinistro specificate come un'istanza della classe [PointF](../pointf/) e la sua larghezza e altezza come un'istanza della classe [SizeF](../sizef/). |
| explicit  [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | Crea una nuova istanza dell'oggetto [RectangleF](./) che rappresenta il rettangolo equivalente a quello specificato. |
| void [set_Height](./set_height/)(**float**) | Imposta l'altezza del rettangolo rappresentato dall'oggetto corrente. |
| void [set_Location](./set_location/)([PointF](../pointf/)) | Imposta la posizione dell'angolo superiore sinistro del rettangolo rappresentato dall'oggetto corrente. |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | Imposta la larghezza e l'altezza del rettangolo rappresentato dall'oggetto corrente. |
| void [set_Width](./set_width/)(**float**) | Imposta la larghezza del rettangolo rappresentato dall'oggetto corrente. |
| void [set_X](./set_x/)(**float**) | Imposta la coordinata X dell'angolo superiore sinistro del rettangolo rappresentato dall'oggetto corrente. |
| void [set_Y](./set_y/)(**float**) | Imposta la coordinata Y dell'angolo superiore sinistro del rettangolo rappresentato dall'oggetto corrente. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Restituisce la rappresentazione stringa dell'oggetto corrente. |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Restituisce un rettangolo che è il risultato dell'unione dei rettangoli specificati. |

## Campi

| Campo | Descrizione |
| --- | --- |
| static [Empty](./empty/) | Un rettangolo vuoto, cioè un rettangolo i cui valori di posizione e dimensione sono zero. |

## Vedi anche

* Spazio dei nomi [System::Drawing](../)
* Libreria [Aspose.Slides](../../)