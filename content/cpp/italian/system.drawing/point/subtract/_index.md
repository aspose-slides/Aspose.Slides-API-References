---
title: Subtract()
second_title: Riferimento API Aspose.Slides per C++
description: Sottrae i valori di larghezza e altezza dell'oggetto Size specificato dai valori delle coordinate X e Y dell'oggetto Point specificato corrispondentemente.
type: docs
weight: 196
url: /it/system.drawing/point/subtract/
---
## Point::Subtract(const Point\&, const Size\&) metodo


Sottrae i valori di larghezza e altezza dell'oggetto [Size](../../size/) specificato dai valori delle coordinate X e Y dell'oggetto [Point](../) specificato corrispondentemente.

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | const [Point](../)\& | Il punto da tradurre |
| size | const [Size](../../size/)\& | L'oggetto [Size](../../size/) che specifica i valori da sottrarre dai valori delle coordinate del **point** |

### Valore di ritorno

Un nuovo oggetto [Point](../) il cui valore della coordinata X è pari al risultato della sottrazione del valore di larghezza di **size** dal valore della coordinata X di **point** e il valore della coordinata Y è pari al risultato della sottrazione del valore di altezza di **size** dal valore della coordinata Y di **point**

## Vedi anche

* Classe [Point](../)
* Classe [Size](../../size/)
* Namespace [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)