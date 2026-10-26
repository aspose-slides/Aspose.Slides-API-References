---
title: SetClip()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta la regione di ritaglio della superficie di disegno rappresentata dall'oggetto Graphics corrente al risultato dell'operazione specificata che combina la regione di ritaglio corrente e la regione specificata.
type: docs
weight: 690
url: /it/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) metodo


Imposta la regione di ritaglio della superficie di disegno rappresentata dall'oggetto [Graphics](../) corrente al risultato dell'operazione specificata che combina la regione di ritaglio corrente e la regione specificata.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | Specifica una regione da combinare |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifica l'operazione di combinazione |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) metodo


Imposta la regione di ritaglio della superficie di disegno rappresentata dall'oggetto [Graphics](../) corrente al risultato dell'operazione specificata che combina la regione di ritaglio corrente e la regione specificata.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Specifica una regione da combinare |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifica l'operazione di combinazione |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) metodo


Imposta la regione di ritaglio della superficie di disegno rappresentata dall'oggetto [Graphics](../) corrente al risultato dell'operazione specificata che combina la regione di ritaglio corrente e la regione specificata.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Specifica una regione da combinare |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifica l'operazione di combinazione |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) metodo


NON IMPLEMENTATO.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) metodo


Imposta la regione di ritaglio della superficie di disegno rappresentata dall'oggetto [Graphics](../) corrente al risultato dell'operazione specificata che combina la regione di ritaglio corrente e la regione specificata da un percorso grafico.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Specifica una regione da combinare |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifica l'operazione di combinazione |

## Vedi anche

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../../region/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)