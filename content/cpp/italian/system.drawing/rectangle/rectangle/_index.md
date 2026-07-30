---
title: Rectangle()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza dell'oggetto Rectangle che rappresenta un rettangolo con coordinate X e Y e valori di larghezza e altezza impostati a 0.
type: docs
weight: 1
url: /it/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() costruttore

Costruisce una nuova istanza dell'oggetto [Rectangle](../) che rappresenta un rettangolo con coordinate X e Y e valori di larghezza e altezza impostati a 0.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) costruttore

Costruisce una nuova istanza dell'oggetto [Rectangle](../) che rappresenta un rettangolo con le coordinate specificate dell'angolo superiore sinistro e la larghezza e l'altezza.

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | Un valore della coordinata X dell'angolo superiore sinistro del rettangolo |
| y | int | Un valore della coordinata Y dell'angolo superiore sinistro del rettangolo |
| width | int | La larghezza del rettangolo |
| height | int | L'altezza del rettangolo |

## Rectangle::Rectangle(const Point\&, const Size\&) costruttore

Costruisce una nuova istanza dell'oggetto [Rectangle](../) che rappresenta un rettangolo con le coordinate dell'angolo superiore sinistro specificate come un'istanza della classe [Point](../../point/) e la larghezza e l'altezza come un'istanza della classe [Size](../../size/).

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| location | const [Point](../../point/)\& | Specifica la posizione dell'angolo superiore sinistro del rettangolo |
| size | const [Size](../../size/)\& | Specifica la larghezza e l'altezza del rettangolo |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle\&) costruttore

Costruisce una nuova istanza dell'oggetto [Rectangle](../) che rappresenta il rettangolo equivalente a quello specificato.

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | Un'istanza della classe **System::Windows::Forms::Screen::Rectangle_** che specifica la posizione e le dimensioni del rettangolo da rappresentare dall'oggetto in fase di costruzione |

## Vedi anche

* Classe [Rectangle](../)
* Classe [Point](../../point/)
* Classe [Size](../../size/)
* Namespace [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)