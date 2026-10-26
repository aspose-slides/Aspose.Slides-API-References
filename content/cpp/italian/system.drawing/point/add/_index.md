---
title: Add()
second_title: Riferimento API Aspose.Slides per C++
description: Aggiunge i valori di larghezza e altezza dell'oggetto Size specificato ai valori delle coordinate X e Y dell'oggetto Point specificato, corrispondentemente.
type: docs
weight: 183
url: /it/system.drawing/point/add/
---
## Point::Add(const Point\&, const Size\&) metodo

Aggiunge i valori di larghezza e altezza dell'oggetto [Size](../../size/) specificato ai valori delle coordinate X e Y dell'oggetto [Point](../) specificato, corrispondentemente.

```cpp
static Point System::Drawing::Point::Add(const Point &point, const Size &size)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | const [Point](../)\& | Il punto da traslare |
| size | const [Size](../../size/)\& | L'oggetto [Size](../../size/) che specifica i valori da aggiungere ai valori delle coordinate del **point** |

### Valore restituito

Un nuovo oggetto [Point](../) il cui valore della coordinata X è pari alla somma del valore della coordinata X di **point** e del valore di larghezza di **size**, e il valore della coordinata Y è pari alla somma del valore della coordinata Y di **point** e del valore di altezza di **size**

## Vedi anche

* Classe [Point](../)
* Classe [Size](../../size/)
* Namespace [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)