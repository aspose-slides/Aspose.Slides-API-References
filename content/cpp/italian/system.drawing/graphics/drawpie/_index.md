---
title: DrawPie()
second_title: Riferimento API di Aspose.Slides per C++
description: Disegna la torta specificata usando la penna specificata sulla superficie rappresentata dall'oggetto corrente.
type: docs
weight: 261
url: /it/system.drawing/graphics/drawpie/
---
## Graphics::DrawPie(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) metodo

Disegna la torta specificata usando la penna specificata sulla superficie rappresentata dall'oggetto corrente.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una penna da usare per disegnare la torta |
| x | **int32_t** | La coordinata X dell'angolo in alto a sinistra del rettangolo che definisce l'ellisse |
| y | **int32_t** | La coordinata Y dell'angolo in alto a sinistra del rettangolo che definisce l'ellisse |
| width | **int32_t** | La larghezza del rettangolo che definisce l'ellisse |
| height | **int32_t** | L'altezza del rettangolo che definisce l'ellisse |
| startAngle | **int32_t** | Angolo in gradi misurato in senso orario dall'asse X al punto di inizio della torta |
| sweepAngle | **int32_t** | Angolo in gradi misurato in senso orario dal **startAngle** al punto finale della torta |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) metodo

Disegna la torta specificata usando la penna specificata sulla superficie rappresentata dall'oggetto corrente.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una penna da usare per disegnare la torta |
| x | **float** | La coordinata X dell'angolo in alto a sinistra del rettangolo che definisce l'ellisse |
| y | **float** | La coordinata Y dell'angolo in alto a sinistra del rettangolo che definisce l'ellisse |
| width | **float** | La larghezza del rettangolo che definisce l'ellisse |
| height | **float** | L'altezza del rettangolo che definisce l'ellisse |
| startAngle | **float** | Angolo in gradi misurato in senso orario dall'asse X al punto di inizio della torta |
| sweepAngle | **float** | Angolo in gradi misurato in senso orario dal **startAngle** al punto finale della torta |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, Rectangle, float, float) metodo

Disegna la torta specificata usando la penna specificata sulla superficie rappresentata dall'oggetto corrente.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una penna da usare per disegnare la torta |
| rect | [Rectangle](../../rectangle/) | Il rettangolo che definisce l'ellisse |
| startAngle | **float** | Angolo in gradi misurato in senso orario dall'asse X al punto di inizio della torta |
| sweepAngle | **float** | Angolo in gradi misurato in senso orario dal **startAngle** al punto finale della torta |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, RectangleF, float, float) metodo

Disegna la torta specificata usando la penna specificata sulla superficie rappresentata dall'oggetto corrente.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una penna da usare per disegnare la torta |
| rect | [RectangleF](../../rectanglef/) | Il rettangolo che definisce l'ellisse |
| startAngle | **float** | Angolo in gradi misurato in senso orario dall'asse X al punto di inizio della torta |
| sweepAngle | **float** | Angolo in gradi misurato in senso orario dal **startAngle** al punto finale della torta |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Pen](../../pen/)
* Classe [Graphics](../)
* Classe [Rectangle](../../rectangle/)
* Classe [RectangleF](../../rectanglef/)
* Spazio dei nomi [System::Drawing](../../)
* Library [Aspose.Slides](../../../)