---
title: Intersect()
second_title: Riferimento API di Aspose.Slides per C++
description: Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'intersezione di questa regione e una regione definita dal rettangolo specificato.
type: docs
weight: 79
url: /it/system.drawing/region/intersect/
---
## Region::Intersect(const RectangleF\&) metodo


Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'intersezione di questa regione e una regione definita dal rettangolo specificato.

```cpp
void System::Drawing::Region::Intersect(const RectangleF &rect)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Un rettangolo che definisce una regione con cui intersecare questa regione |

## Region::Intersect(const Rectangle\&) metodo


Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'intersezione di questa regione e una regione definita dal rettangolo specificato.

```cpp
void System::Drawing::Region::Intersect(const Rectangle &rect)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Un rettangolo che definisce una regione con cui intersecare questa regione |

## Region::Intersect(const SharedPtr\<Drawing2D::GraphicsPath\>\&) metodo


Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'intersezione di questa regione e una regione definita dal percorso specificato.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Un percorso che definisce una regione con cui intersecare questa regione |

## Region::Intersect(const SharedPtr\<Region\>\&) metodo


Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'intersezione di questa regione e la regione specificata.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Region> &region)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Una regione con cui intersecare questa regione |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RectangleF](../../rectanglef/)
* Classe [Region](../)
* Classe [Rectangle](../../rectangle/)
* Classe [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)