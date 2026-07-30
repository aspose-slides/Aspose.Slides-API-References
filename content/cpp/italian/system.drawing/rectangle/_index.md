---
title: Rectangle
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un'area rettangolare di un'immagine definita dalle coordinate intere X e Y dell'angolo superiore sinistro e dalla sua larghezza e altezza. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire oggetti di questo tipo."
type: docs
weight: 235
url: /it/system.drawing/rectangle/
---
## Classe Rectangle

Rappresenta un'area rettangolare di un'immagine definita dalle coordinate intere X e Y dell'angolo superiore sinistro e dalla sua larghezza e altezza. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe [System::SmartPtr](../../system/smartptr/) per gestire oggetti di questo tipo.

```cpp
class Rectangle
```

## Metodi

| Method | Description |
| --- | --- |
| static [Rectangle](./) [Ceiling](./ceiling/)(const [RectangleF](../rectanglef/)\&) | Costruisce un oggetto [Rectangle](./) dall'oggetto [RectangleF](../rectanglef/) specificato arrotondando i valori di posizione e dimensione dell'oggetto [RectangleF](../rectanglef/) al prossimo valore intero superiore. |
| **bool** [Contains](./contains/)(int, int) const | Determina se il punto specificato si trova all'interno del rettangolo rappresentato dall'oggetto corrente. |
| **bool** [Contains](./contains/)(const [Point](../point/)\&) const | Determina se il punto specificato si trova all'interno del rettangolo rappresentato dall'oggetto corrente. |
| **bool** [Contains](./contains/)(const [Rectangle](./)\&) const | Determina se il rettangolo specificato si trova all'interno del rettangolo rappresentato dall'oggetto corrente. |
| **bool** [Equals](./equals/)(const [Rectangle](./)\&) const | Determina se i rettangoli rappresentati dall'oggetto corrente e dall'oggetto specificato sono identici. |
| static [Rectangle](./) [FromLTRB](./fromltrb/)(int, int, int, int) | Costruisce un nuovo oggetto [Rectangle](./) che rappresenta un rettangolo con le posizioni dei bordi specificate. |
| int [get_Bottom](./get_bottom/)() const | Restituisce la coordinata y del bordo inferiore del rettangolo rappresentato dall'oggetto corrente. |
| int [get_Height](./get_height/)() const | Restituisce l'altezza del rettangolo rappresentato dall'oggetto corrente. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determina se le coordinate X e Y dell'angolo in alto a sinistra del rettangolo rappresentato dall'oggetto corrente, così come la sua larghezza e altezza, hanno valore 0. |
| int [get_Left](./get_left/)() const | Restituisce la coordinata X del bordo sinistro del rettangolo rappresentato dall'oggetto corrente. |
| [Point](../point/) [get_Location](./get_location/)() const | Restituisce un'istanza della classe [Point](../point/) che specifica la posizione dell'angolo in alto a sinistra del rettangolo rappresentato dall'oggetto corrente. |
| int [get_Right](./get_right/)() const | Restituisce la coordinata X del bordo destro del rettangolo rappresentato dall'oggetto corrente. |
| [Size](../size/) [get_Size](./get_size/)() const | Restituisce un'istanza della classe [Size](../size/) che specifica la larghezza e l'altezza del rettangolo rappresentato dall'oggetto corrente. |
| int [get_Top](./get_top/)() const | Restituisce la coordinata Y del bordo superiore del rettangolo rappresentato dall'oggetto corrente. |
| int [get_Width](./get_width/)() const | Restituisce la larghezza del rettangolo rappresentato dall'oggetto corrente. |
| int [get_X](./get_x/)() const | Restituisce la coordinata X dell'angolo in alto a sinistra del rettangolo rappresentato dall'oggetto corrente. |
| int [get_Y](./get_y/)() const | Restituisce la coordinata Y dell'angolo in alto a sinistra del rettangolo rappresentato dall'oggetto corrente. |
| int [GetHashCode](./gethashcode/)() const | Restituisce un codice hash dell'oggetto corrente. |
| void [Inflate](./inflate/)(int, int) | Aumenta la larghezza e l'altezza del rettangolo rappresentato dall'oggetto corrente, mantenendo la posizione del centro geometrico del rettangolo. La larghezza e l'altezza vengono aumentate in entrambe le direzioni delle quantità specificate. |
| void [Inflate](./inflate/)(const [Size](../size/)\&) | Aumenta la larghezza e l'altezza del rettangolo rappresentato dall'oggetto corrente, mantenendo la posizione del centro geometrico del rettangolo. La larghezza e l'altezza vengono aumentate in entrambe le direzioni delle quantità specificate dai valori di larghezza e altezza dell'oggetto dimensione specificato corrispondentemente. |
| static [Rectangle](./) [Inflate](./inflate/)(const [Rectangle](./)\&, int, int) | Aumenta la larghezza e l'altezza del rettangolo rappresentato dall'oggetto specificato, mantenendo la posizione del centro geometrico del rettangolo. La larghezza e l'altezza vengono aumentate in entrambe le direzioni delle quantità specificate. |
| void [Intersect](./intersect/)(const [Rectangle](./)\&) | Sostituisce il rettangolo rappresentato dall'oggetto corrente con il rettangolo risultante dalla sua intersezione con il rettangolo rappresentato dall'oggetto specificato. |
| static [Rectangle](./) [Intersect](./intersect/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Restituisce un rettangolo che è il risultato dell'intersezione dei rettangoli specificati. |
| **bool** [IntersectsWith](./intersectswith/)(const [Rectangle](./)\&) | Determina se i rettangoli rappresentati dall'oggetto corrente e da quello specificato si intersecano. |
| void [Offset](./offset/)(const [Point](../point/)\&) | Sposta la posizione del rettangolo rappresentato dall'oggetto corrente delle quantità specificate. |
| void [Offset](./offset/)(int, int) | Sposta la posizione del rettangolo rappresentato dall'oggetto corrente delle quantità specificate. |
| [operator RectangleF](./operator_rectanglef/)() const | Restituisce un oggetto [RectangleF](../rectanglef/) che rappresenta un rettangolo equivalente al rettangolo rappresentato dall'oggetto corrente. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Restituisce sempre true. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Restituisce sempre false. |
| [Rectangle](./rectangle/)() | Costruisce una nuova istanza dell'oggetto [Rectangle](./) che rappresenta un rettangolo con le coordinate X e Y e i valori di larghezza e altezza impostati a 0. |
| [Rectangle](./rectangle/)(int, int, int, int) | Costruisce una nuova istanza dell'oggetto [Rectangle](./) che rappresenta un rettangolo con le coordinate specificate dell'angolo in alto a sinistra e la larghezza e l'altezza. |
| [Rectangle](./rectangle/)(const [Point](../point/)\&, const [Size](../size/)\&) | Costruisce una nuova istanza dell'oggetto [Rectangle](./) che rappresenta un rettangolo con le coordinate dell'angolo in alto a sinistra specificate come istanza della classe [Point](../point/) e la sua larghezza e altezza come istanza della classe [Size](../size/). |
| [Rectangle](./rectangle/)(const **System::Windows::Forms::Screen::Rectangle_**\&) | Costruisce una nuova istanza dell'oggetto [Rectangle](./) che rappresenta il rettangolo equivalente a quello specificato. |
| static [Rectangle](./) [Round](./round/)(const [RectangleF](../rectanglef/)\&) | Costruisce un oggetto [Rectangle](./) dall'oggetto [RectangleF](../rectanglef/) specificato arrotondando i valori di posizione e dimensione dell'oggetto [RectangleF](../rectanglef/) al valore intero più vicino. |
| void [set_Height](./set_height/)(int) | Imposta l'altezza del rettangolo rappresentato dall'oggetto corrente. |
| void [set_Location](./set_location/)([Point](../point/)) | Imposta la posizione dell'angolo in alto a sinistra del rettangolo rappresentato dall'oggetto corrente. |
| void [set_Size](./set_size/)([Size](../size/)) | Imposta la larghezza e l'altezza del rettangolo rappresentato dall'oggetto corrente. |
| void [set_Width](./set_width/)(int) | Imposta la larghezza del rettangolo rappresentato dall'oggetto corrente. |
| void [set_X](./set_x/)(int) | Imposta la coordinata X dell'angolo in alto a sinistra del rettangolo rappresentato dall'oggetto corrente. |
| void [set_Y](./set_y/)(int) | Imposta la coordinata Y dell'angolo in alto a sinistra del rettangolo rappresentato dall'oggetto corrente. |
| [String](../../system/string/) [ToString](./tostring/)() const | Restituisce la rappresentazione stringa dell'oggetto corrente. |
| static [Rectangle](./) [Truncate](./truncate/)(const [RectangleF](../rectanglef/)\&) | Costruisce un oggetto [Rectangle](./) dall'oggetto [RectangleF](../rectanglef/) specificato troncando i valori di posizione e dimensione dell'oggetto [RectangleF](../rectanglef/) al prossimo valore intero inferiore. |
| static [Rectangle](./) [Union](./union/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Restituisce un rettangolo che è il risultato dell'unione dei rettangoli specificati. |

## Campi

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Un rettangolo vuoto, cioè un rettangolo i cui valori di posizione e dimensione sono zero. |

## Vedi anche

* Namespace [System::Drawing](../)
* Libreria [Aspose.Slides](../../)