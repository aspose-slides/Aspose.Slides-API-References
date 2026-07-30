---
title: AddPie()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge il contorno specificato della forma a torta al percorso rappresentato dall'oggetto corrente.
type: docs
weight: 209
url: /it/system.drawing.drawing2d/graphicspath/addpie/
---
## GraphicsPath::AddPie(float, float, float, float, float, float) metodo

Aggiunge il contorno specificato della forma a torta al percorso rappresentato dall'oggetto corrente.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata X dell'angolo superiore sinistro del rettangolo che delimita l'ellisse da cui viene disegnata la torta |
| y | **float** | La coordinata Y dell'angolo superiore sinistro del rettangolo che delimita l'ellisse da cui viene disegnata la torta |
| width | **float** | La larghezza dell'angolo superiore sinistro del rettangolo che delimita l'ellisse da cui viene disegnata la torta |
| height | **float** | L'altezza dell'angolo superiore sinistro del rettangolo che delimita l'ellisse da cui viene disegnata la torta |
| startAngle | **float** | Specifica l'angolo di partenza della torta in gradi, misurato in senso orario dall'asse X |
| sweepAngle | **float** | Specifica l'angolo compreso tra l'angolo di partenza e la fine della torta |

## GraphicsPath::AddPie(int, int, int, int, float, float) metodo

Aggiunge il contorno specificato della forma a torta al percorso rappresentato dall'oggetto corrente.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(int x, int y, int width, int height, float startAngle, float sweepAngle)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata X dell'angolo superiore sinistro del rettangolo che delimita l'ellisse da cui viene disegnata la torta |
| y | int | La coordinata Y dell'angolo superiore sinistro del rettangolo che delimita l'ellisse da cui viene disegnata la torta |
| width | int | La larghezza dell'angolo superiore sinistro del rettangolo che delimita l'ellisse da cui viene disegnata la torta |
| height | int | L'altezza dell'angolo superiore sinistro del rettangolo che delimita l'ellisse da cui viene disegnata la torta |
| startAngle | **float** | Specifica l'angolo di partenza della torta in gradi, misurato in senso orario dall'asse X |
| sweepAngle | **float** | Specifica l'angolo compreso tra l'angolo di partenza e la fine della torta |

## GraphicsPath::AddPie(const Rectangle\&, float, float) metodo

Aggiunge il contorno specificato della forma a torta al percorso rappresentato dall'oggetto corrente.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(const Rectangle &rect, float startAngle, float sweepAngle)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | Il rettangolo che delimita l'ellisse da cui viene disegnata la torta |
| startAngle | **float** | Specifica l'angolo di partenza della torta in gradi, misurato in senso orario dall'asse X |
| sweepAngle | **float** | Specifica l'angolo compreso tra l'angolo di partenza e la fine della torta |

## Vedi anche

* Classe [GraphicsPath](../)
* Classe [Rectangle](../../../system.drawing/rectangle/)
* Spazio dei nomi [System::Drawing::Drawing2D](../../)
* Libreria [Aspose.Slides](../../../)