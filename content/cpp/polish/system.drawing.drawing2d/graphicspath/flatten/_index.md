---
title: Flatten()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Spłaszcza każdą krzywą w ścieżce, przekształcając ją w serię połączonych linii. Wartość spłaszczenia 0.25 jest używana.
type: docs
weight: 391
url: /pl/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() metoda

Spłaszcza każdą krzywą w ścieżce, przekształcając ją w serię połączonych linii. Wartość spłaszczenia 0.25 jest używana.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) metoda

Spłaszcza każdą krzywą w ścieżce, przekształcając ją w serię połączonych linii. Wartość spłaszczenia 0.25 jest używana.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Macierz transformacji stosowana do ścieżki przed spłaszczeniem |

## GraphicsPath::Flatten(const MatrixPtr\&, float) metoda

Spłaszcza każdą krzywą w ścieżce, przekształcając ją w serię połączonych linii.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Macierz transformacji stosowana do ścieżki przed spłaszczeniem |
| flatness | **float** | Określa maksymalny dopuszczalny błąd pomiędzy krzywą a jej spłaszczonym przybliżeniem |

## Zobacz także

* Typedef [MatrixPtr](../../matrixptr/)
* Klasa [GraphicsPath](../)
* Przestrzeń nazw [System::Drawing::Drawing2D](../../)
* Biblioteka [Aspose.Slides](../../../)