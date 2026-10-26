---
title: Flatten()
second_title: Aspose.Slides pro C++ API Reference
description: Zplošťuje každou křivku v cestě převedením na řadu propojených úseček. Hodnota plochosti 0.25 je použita.
type: docs
weight: 391
url: /cs/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() metoda


Zploští každou křivku v cestě převedením na řadu propojených úseček. Hodnota plochosti 0.25 je použita.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) metoda


Zploští každou křivku v cestě převedením na řadu propojených úseček. Hodnota plochosti 0.25 je použita.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Transformační matice, která se použije na cestu před zploštěním |

## GraphicsPath::Flatten(const MatrixPtr\&, float) metoda


Zploští každou křivku v cestě převedením na řadu propojených úseček.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Transformační matice, která se použije na cestu před zploštěním |
| flatness | **float** | Určuje maximální povolenou chybu mezi křivkou a jejím zploštěným přiblížením |

## Viz také

* Definice typu [MatrixPtr](../../matrixptr/)
* Třída [GraphicsPath](../)
* Jmenný prostor [System::Drawing::Drawing2D](../../)
* Knihovna [Aspose.Slides](../../../)