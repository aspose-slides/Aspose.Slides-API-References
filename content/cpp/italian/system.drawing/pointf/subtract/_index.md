---
title: Subtract()
second_title: Aspose.Slides per C++ Riferimento API
description: Sottrae i valori di larghezza e altezza dell'oggetto SizeF specificato dai valori delle coordinate X e Y dell'oggetto PointF specificato, corrispondentemente.
type: docs
weight: 157
url: /it/system.drawing/pointf/subtract/
---
## PointF::Subtract(const PointF\&, const SizeF\&) metodo


Sottrae i valori di larghezza e altezza dell'oggetto [SizeF](../../sizef/) specificato dai valori delle coordinate X e Y dell'oggetto [PointF](../) specificato, corrispondentemente.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const SizeF &size)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | const [PointF](../)\& | Il punto da tradurre |
| size | const [SizeF](../../sizef/)\& | L'oggetto [SizeF](../../sizef/) che specifica i valori da sottrarre dai valori delle coordinate del **point** |

### Valore di ritorno

Un nuovo oggetto [PointF](../) il cui valore della coordinata X è uguale al risultato della sottrazione del valore di larghezza di **size** dal valore della coordinata X di **point** e il valore della coordinata Y è uguale al risultato della sottrazione del valore di altezza di **size** dal valore della coordinata Y di **point**.

## PointF::Subtract(const PointF\&, const Size\&) metodo


Sottrae i valori di larghezza e altezza dell'oggetto [Size](../../size/) specificato dai valori delle coordinate X e Y dell'oggetto [PointF](../) specificato, corrispondentemente.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const Size &size)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | const [PointF](../)\& | Il punto da tradurre |
| size | const [Size](../../size/)\& | L'oggetto [Size](../../size/) che specifica i valori da sottrarre dai valori delle coordinate del **point** |

### Valore di ritorno

Un nuovo oggetto [PointF](../) il cui valore della coordinata X è uguale al risultato della sottrazione del valore di larghezza di **size** dal valore della coordinata X di **point** e il valore della coordinata Y è uguale al risultato della sottrazione del valore di altezza di **size** dal valore della coordinata Y di **point**.

## Vedi anche

* Classe [PointF](../)
* Classe [SizeF](../../sizef/)
* Classe [Size](../../size/)
* Spazio dei nomi [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)