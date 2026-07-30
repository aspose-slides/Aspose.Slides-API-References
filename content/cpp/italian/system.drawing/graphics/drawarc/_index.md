---
title: DrawArc()
second_title: Riferimento API di Aspose.Slides per C++
description: Disegna l'arco specificato usando la penna specificata sulla superficie rappresentata dall'oggetto corrente.
type: docs
weight: 248
url: /it/system.drawing/graphics/drawarc/
---
## Graphics::DrawArc(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) metodo


Disegna l'arco specificato usando la pen specificata sulla superficie rappresentata dall'oggetto corrente.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una pen da usare quando si disegna l'arco |
| x | **int32_t** | La coordinata X dell'angolo superiore sinistro del rettangolo che definisce l'ellisse |
| y | **int32_t** | La coordinata Y dell'angolo superiore sinistro del rettangolo che definisce l'ellisse |
| width | **int32_t** | La larghezza del rettangolo che definisce l'ellisse |
| height | **int32_t** | L'altezza del rettangolo che definisce l'ellisse |
| startAngle | **int32_t** | Angolo in gradi misurato in senso orario dall'asse X al punto di partenza dell'arco |
| sweepAngle | **int32_t** | Angolo in gradi misurato in senso orario dal **startAngle** al punto finale dell'arco |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) metodo


Disegna l'arco specificato usando la pen specificata sulla superficie rappresentata dall'oggetto corrente.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una pen da usare quando si disegna l'arco |
| x | **float** | La coordinata X dell'angolo superiore sinistro del rettangolo che definisce l'ellisse |
| y | **float** | La coordinata Y dell'angolo superiore sinistro del rettangolo che definisce l'ellisse |
| width | **float** | La larghezza del rettangolo che definisce l'ellisse |
| height | **float** | L'altezza del rettangolo che definisce l'ellisse |
| startAngle | **float** | Angolo in gradi misurato in senso orario dall'asse X al punto di partenza dell'arco |
| sweepAngle | **float** | Angolo in gradi misurato in senso orario dal **startAngle** al punto finale dell'arco |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, Rectangle, float, float) metodo


Disegna l'arco specificato usando la pen specificata sulla superficie rappresentata dall'oggetto corrente.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una pen da usare quando si disegna l'arco |
| rect | [Rectangle](../../rectangle/) | Il rettangolo che definisce l'ellisse |
| startAngle | **float** | Angolo in gradi misurato in senso orario dall'asse X al punto di partenza dell'arco |
| sweepAngle | **float** | Angolo in gradi misurato in senso orario dal **startAngle** al punto finale dell'arco |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, RectangleF, float, float) metodo


Disegna l'arco specificato usando la pen specificata sulla superficie rappresentata dall'oggetto corrente.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una pen da usare quando si disegna l'arco |
| rect | [RectangleF](../../rectanglef/) | Il rettangolo che definisce l'ellisse |
| startAngle | **float** | Angolo in gradi misurato in senso orario dall'asse X al punto di partenza dell'arco |
| sweepAngle | **float** | Angolo in gradi misurato in senso orario dal **startAngle** al punto finale dell'arco |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Pen](../../pen/)
* Classe [Graphics](../)
* Classe [Rectangle](../../rectangle/)
* Classe [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)