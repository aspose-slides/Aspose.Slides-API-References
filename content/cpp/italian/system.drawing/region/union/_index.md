---
title: Union()
second_title: Riferimento API Aspose.Slides per C++
description: Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'operazione di unione di questa regione e una regione definita dal rettangolo specificato.
type: docs
weight: 53
url: /it/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) metodo


Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'operazione di unione di questa regione e una regione definita dal rettangolo specificato.

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Un rettangolo che definisce una regione da unire a questa regione |

## Region::Union(const Rectangle\&) metodo


Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'unione di questa regione e una regione definita dal rettangolo specificato.

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Un rettangolo che definisce una regione da unire a questa regione |

## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) metodo


Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'unione di questa regione e una regione definita dal percorso specificato.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Un percorso che definisce una regione da unire a questa regione |

## Region::Union(const SharedPtr\<Region\>\&) metodo


Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'unione di questa regione e la regione specificata.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Una regione da unire a questa regione |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RectangleF](../../rectanglef/)
* Classe [Region](../)
* Classe [Rectangle](../../rectangle/)
* Classe [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)