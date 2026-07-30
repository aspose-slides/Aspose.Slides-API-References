---
title: Inflate()
second_title: Riferimento API Aspose.Slides per C++
description: Aumenta la larghezza e l'altezza del rettangolo rappresentato dall'oggetto corrente, mantenendo la posizione del centro geometrico del rettangolo. La larghezza e l'altezza vengono aumentate in entrambe le direzioni delle quantità specificate.
type: docs
weight: 261
url: /it/system.drawing/rectanglef/inflate/
---
## RectangleF::Inflate(float, float) metodo


Aumenta la larghezza e l'altezza del rettangolo rappresentato dall'oggetto corrente, mantenendo la posizione del centro geometrico del rettangolo. La larghezza e l'altezza vengono aumentate in entrambe le direzioni delle quantità specificate.

```cpp
void System::Drawing::RectangleF::Inflate(float width, float height)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | **float** | La quantità di cui aumentare la larghezza del rettangolo in entrambe le direzioni |
| height | **float** | La quantità di cui aumentare l'altezza del rettangolo in entrambe le direzioni |

## RectangleF::Inflate(const SizeF\&) metodo


Aumenta la larghezza e l'altezza del rettangolo rappresentato dall'oggetto corrente, mantenendo la posizione del centro geometrico del rettangolo. La larghezza e l'altezza vengono aumentate in entrambe le direzioni dalle quantità specificate dai valori width e height dell'oggetto size specificato corrispondentemente.

```cpp
void System::Drawing::RectangleF::Inflate(const SizeF &size)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | const [SizeF](../../sizef/)\& | L'oggetto [SizeF](../../sizef/) che specifica le quantità di cui aumentare la larghezza e l'altezza del rettangolo |

## RectangleF::Inflate(const RectangleF\&, float, float) metodo


Aumenta la larghezza e l'altezza del rettangolo rappresentato dall'oggetto specificato, mantenendo la posizione del centro geometrico del rettangolo. La larghezza e l'altezza vengono aumentate in entrambe le direzioni delle quantità specificate.

```cpp
static RectangleF System::Drawing::RectangleF::Inflate(const RectangleF &rect, float x, float y)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | Un rettangolo da gonfiare |
| x | **float** | La quantità di cui aumentare la larghezza del rettangolo in entrambe le direzioni |
| y | **float** | La quantità di cui aumentare l'altezza del rettangolo in entrambe le direzioni |

### Valore di ritorno

L'oggetto [RectangleF](../) che rappresenta il rettangolo ingrandito

## Vedi anche

* Classe [RectangleF](../)
* Classe [SizeF](../../sizef/)
* Spazio dei nomi [System::Drawing](../../)
* Library [Aspose.Slides](../../../)