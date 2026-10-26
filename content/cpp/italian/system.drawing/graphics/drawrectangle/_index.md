---
title: DrawRectangle()
second_title: Riferimento API di Aspose.Slides per C++
description: Disegna il rettangolo specificato utilizzando la penna specificata sulla superficie rappresentata dall'oggetto corrente.
type: docs
weight: 287
url: /it/system.drawing/graphics/drawrectangle/
---
## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, int, int, int, int) metodo

Disegna il rettangolo specificato utilizzando la penna specificata sulla superficie rappresentata dall'oggetto corrente.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, int x, int y, int width, int height)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una penna da utilizzare durante il disegno del rettangolo |
| x | int | La coordinata X dell'angolo in alto a sinistra del rettangolo da disegnare |
| y | int | La coordinata Y dell'angolo in alto a sinistra del rettangolo da disegnare |
| width | int | La larghezza del rettangolo da disegnare |
| height | int | L'altezza del rettangolo da disegnare |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, float, float, float, float) metodo

Disegna il rettangolo specificato utilizzando la penna specificata sulla superficie rappresentata dall'oggetto corrente.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, float x, float y, float width, float height)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una penna da utilizzare durante il disegno del rettangolo |
| x | **float** | La coordinata X dell'angolo in alto a sinistra del rettangolo da disegnare |
| y | **float** | La coordinata Y dell'angolo in alto a sinistra del rettangolo da disegnare |
| width | **float** | La larghezza del rettangolo da disegnare |
| height | **float** | L'altezza del rettangolo da disegnare |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, Rectangle) metodo

Disegna il rettangolo specificato utilizzando la penna specificata sulla superficie rappresentata dall'oggetto corrente.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, Rectangle rect)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una penna da utilizzare durante il disegno del rettangolo |
| rect | [Rectangle](../../rectangle/) | Un oggetto [Rectangle](../../rectangle/) che specifica la posizione e le dimensioni del rettangolo da disegnare |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Pen](../../pen/)
* Classe [Graphics](../)
* Classe [Rectangle](../../rectangle/)
* Spazio dei nomi [System::Drawing](../../)
* Library [Aspose.Slides](../../../)