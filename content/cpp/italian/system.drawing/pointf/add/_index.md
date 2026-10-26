---
title: Add()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge i valori di larghezza e altezza dell'oggetto SizeF specificato ai valori delle coordinate X e Y dell'oggetto PointF specificato, rispettivamente.
type: docs
weight: 144
url: /it/system.drawing/pointf/add/
---
## PointF::Add(const PointF\&, const SizeF\&) metodo


Aggiunge i valori di larghezza e altezza dell'oggetto [SizeF](../../sizef/) specificato ai valori delle coordinate X e Y dell'oggetto [PointF](../) specificato, rispettivamente.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const SizeF &size)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | const [PointF](../)\& | Il punto da traslare |
| size | const [SizeF](../../sizef/)\& | L'oggetto [SizeF](../../sizef/) che specifica i valori da aggiungere ai valori delle coordinate del **point** |

### Valore restituito

Un nuovo oggetto [PointF](../) il cui valore della coordinata X è uguale alla somma del valore della coordinata X di **point** e del valore di larghezza di **size**, e il valore della coordinata Y è uguale alla somma del valore della coordinata Y di **point** e del valore di altezza di **size**.

## PointF::Add(const PointF\&, const Size\&) metodo


Aggiunge i valori di larghezza e altezza dell'oggetto [Size](../../size/) specificato ai valori delle coordinate X e Y dell'oggetto [PointF](../) specificato, rispettivamente.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const Size &size)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | const [PointF](../)\& | Il punto da traslare |
| size | const [Size](../../size/)\& | L'oggetto [Size](../../size/) che specifica i valori da aggiungere ai valori delle coordinate del **point** |

### Valore restituito

Un nuovo oggetto [PointF](../) il cui valore della coordinata X è uguale alla somma del valore della coordinata X di **point** e del valore di larghezza di **size**, e il valore della coordinata Y è uguale alla somma del valore della coordinata Y di **point** e del valore di altezza di **size**.

## Vedi anche

* Classe [PointF](../)
* Classe [SizeF](../../sizef/)
* Classe [Size](../../size/)
* Spazio dei nomi [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)