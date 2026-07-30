---
title: Point()
second_title: Aspose.Slides per C++ Riferimento API
description: Crea un nuovo oggetto Point e inizializza i valori delle coordinate X e Y a 0.
type: docs
weight: 1
url: /it/system.drawing/point/point/
---
## Point::Point() costruttore

Crea un nuovo oggetto [Point](../) e inizializza i valori delle coordinate X e Y a 0.

```cpp
System::Drawing::Point::Point()
```

## Point::Point(int, int) costruttore

Crea un nuovo oggetto [Point](../) e lo inizializza con i valori specificati.

```cpp
System::Drawing::Point::Point(int x, int y)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | Il valore della coordinata X |
| y | int | Il valore della coordinata Y |

## Point::Point(const Size\&) costruttore

Crea un nuovo oggetto [Point](../) e inizializza i valori delle coordinate X e Y con i valori di larghezza e altezza dell'oggetto [SizeF](../../sizef/) specificato, rispettivamente.

```cpp
System::Drawing::Point::Point(const Size &size)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| size | const [Size](../../size/)\& | Un oggetto [SizeF](../../sizef/) i cui valori di larghezza e altezza vengono usati per inizializzare i valori delle coordinate X e Y dell'oggetto [Point](../) in fase di creazione |

## Point::Point(int) costruttore

Crea un nuovo oggetto [Point](../) e inizializza il valore della coordinata X con un valore formato dagli 16 bit più alti del intero a 32 bit specificato e il valore della coordinata Y con un valore formato dai 16 bit più bassi del valore intero a 32 bit specificato.

```cpp
System::Drawing::Point::Point(int dw)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dw | int | Il valore intero a 32 bit i cui 16 bit più alti specificano il valore della coordinata X e i 16 bit più bassi specificano il valore della coordinata Y dell'oggetto in fase di creazione |

## Vedi anche

* Classe [Point](../)
* Classe [Size](../../size/)
* Spazio dei nomi [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)