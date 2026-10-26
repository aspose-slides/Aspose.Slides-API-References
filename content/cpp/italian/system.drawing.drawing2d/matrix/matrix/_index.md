---
title: Matrix()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una nuova istanza della classe Matrix che rappresenta una matrice identità.
type: docs
weight: 1
url: /it/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() costruttore


Costruisce una nuova istanza della classe [Matrix](../) che rappresenta una matrice identità.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) costruttore


Costruisce una nuova istanza della classe [Matrix](../) e la inizializza con i valori specificati.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| m11 | **float** | Il valore della prima riga prima colonna |
| m12 | **float** | Il valore della prima riga seconda colonna |
| m21 | **float** | Il valore della seconda riga prima colonna |
| m22 | **float** | Il valore della seconda riga seconda colonna |
| dx | **float** | Il valore della terza riga prima colonna |
| dy | **float** | Il valore della terza riga seconda colonna |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) costruttore


Costruisce una nuova istanza della classe [Matrix](../) per la trasformazione geometrica definita dal rettangolo e dall&apos;array di punti specificati.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) costruttore


Costruisce una nuova istanza della classe [Matrix](../) per la trasformazione geometrica definita dal rettangolo e dall&apos;array di punti specificati.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Matrix](../)
* Classe [Rectangle](../../../system.drawing/rectangle/)
* Classe [Point](../../../system.drawing/point/)
* Classe [RectangleF](../../../system.drawing/rectanglef/)
* Classe [PointF](../../../system.drawing/pointf/)
* Spazio dei nomi [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)