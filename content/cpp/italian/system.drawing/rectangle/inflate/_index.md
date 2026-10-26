---
title: Inflate()
second_title: Riferimento API Aspose.Slides per C++
description: Aumenta la larghezza e l'altezza del rettangolo rappresentato dall'oggetto corrente, mantenendo la posizione del centro geometrico del rettangolo. La larghezza e l'altezza vengono aumentate in entrambe le direzioni degli importi specificati.
type: docs
weight: 261
url: /it/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(int, int) metodo

Aumenta la larghezza e l'altezza del rettangolo rappresentato dall'oggetto corrente, mantenendo la posizione del centro geometrico del rettangolo. La larghezza e l'altezza vengono aumentate in entrambe le direzioni degli importi specificati.

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | L'importo con cui la larghezza del rettangolo deve essere aumentata in entrambe le direzioni |
| height | int | L'importo con cui l'altezza del rettangolo deve essere aumentata in entrambe le direzioni |

## Rectangle::Inflate(const Size\&) metodo

Aumenta la larghezza e l'altezza del rettangolo rappresentato dall'oggetto corrente, mantenendo la posizione del centro geometrico del rettangolo. La larghezza e l'altezza vengono aumentate in entrambe le direzioni degli importi specificati dai valori di larghezza e altezza dell'oggetto size specificato, corrispondentemente.

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | const [Size](../../size/)\& | L'oggetto [Size](../../size/) che specifica gli importi con cui aumentare la larghezza e l'altezza del rettangolo |

## Rectangle::Inflate(const Rectangle\&, int, int) metodo

Aumenta la larghezza e l'altezza del rettangolo rappresentato dall'oggetto specificato, mantenendo la posizione del centro geometrico del rettangolo. La larghezza e l'altezza vengono aumentate in entrambe le direzioni degli importi specificati.

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | Un rettangolo da ingrandire |
| x | int | L'importo con cui la larghezza del rettangolo deve essere aumentata in entrambe le direzioni |
| y | int | L'importo con cui l'altezza del rettangolo deve essere aumentata in entrambe le direzioni |

### Valore di ritorno

L'oggetto [Rectangle](../) che rappresenta il rettangolo ingrandito

## Vedi anche

* Classe [Rectangle](../)
* Classe [Size](../../size/)
* Namespace [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)