---
title: RectangleF()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una nuova istanza dell'oggetto RectangleF che rappresenta un rettangolo con coordinate X e Y e valori di larghezza e altezza impostati a 0.
type: docs
weight: 1
url: /it/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() costruttore


Crea una nuova istanza dell'oggetto [RectangleF](../) che rappresenta un rettangolo con coordinate X e Y e valori di larghezza e altezza impostati a 0.

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) costruttore


Crea una nuova istanza dell'oggetto [RectangleF](../) che rappresenta un rettangolo con le coordinate specificate dell'angolo superiore sinistro e larghezza e altezza.

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | Un valore della coordinata X dell'angolo superiore sinistro del rettangolo |
| y | **float** | Un valore della coordinata Y dell'angolo superiore sinistro del rettangolo |
| width | **float** | La larghezza del rettangolo |
| height | **float** | L'altezza del rettangolo |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) costruttore


Crea una nuova istanza dell'oggetto [RectangleF](../) che rappresenta un rettangolo con le coordinate dell'angolo superiore sinistro specificate come istanza della classe [PointF](../../pointf/) e la larghezza e altezza come istanza della classe [SizeF](../../sizef/).

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | Specifica la posizione dell'angolo superiore sinistro del rettangolo |
| size | const [SizeF](../../sizef/)\& | Specifica la larghezza e l'altezza del rettangolo |

## RectangleF::RectangleF(const Rectangle\&) costruttore


Crea una nuova istanza dell'oggetto [RectangleF](../) che rappresenta il rettangolo equivalente a quello specificato.

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Un'istanza della classe [Rectangle](../../rectangle/) che specifica la posizione e le dimensioni del rettangolo da rappresentare dall'oggetto in costruzione |

## Vedi anche

* Classe [RectangleF](../)
* Classe [PointF](../../pointf/)
* Classe [SizeF](../../sizef/)
* Classe [Rectangle](../../rectangle/)
* Spazio dei nomi [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)