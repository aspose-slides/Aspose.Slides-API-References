---
title: Flatten()
second_title: Riferimento API di Aspose.Slides per C++
description: Appiattisce ogni curva nel percorso convertendola in una serie di linee connesse. Il valore di flatness di 0.25 è usato.
type: docs
weight: 391
url: /it/system.drawing.drawing2d/graphicspath/flatten/
---
## Metodo GraphicsPath::Flatten()


Appiattisce ogni curva nel percorso convertendola in una serie di linee connesse. Il valore di flatness di 0.25 è usato.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## Metodo GraphicsPath::Flatten(const MatrixPtr\&)

Appiattisce ogni curva nel percorso convertendola in una serie di linee connesse. Il valore di flatness di 0.25 è usato.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | La matrice di trasformazione da applicare al percorso prima dell'appiattimento |

## Metodo GraphicsPath::Flatten(const MatrixPtr\&, float)


Appiattisce ogni curva nel percorso convertendola in una serie di linee connesse.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | La matrice di trasformazione da applicare al percorso prima dell'appiattimento |
| flatness | **float** | Specifica l'errore massimo consentito tra la curva e la sua approssimazione appiattita |

## Vedi anche

* Typedef [MatrixPtr](../../matrixptr/)
* Classe [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Libreria [Aspose.Slides](../../../)