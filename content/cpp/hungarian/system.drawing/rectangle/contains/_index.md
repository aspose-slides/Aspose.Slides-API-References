---
title: Contains()
second_title: Aspose.Slides C++ API referenciája
description: Megállapítja, hogy a megadott pont a jelenlegi objektum által képviselt téglalapon belül helyezkedik-e.
type: docs
weight: 248
url: /hu/system.drawing/rectangle/contains/
---
## Rectangle::Contains(int, int) const metódus

Meghatározza, hogy a megadott pont a jelenlegi objektum által képviselt téglalapon belül helyezkedik-e el.

```cpp
bool System::Drawing::Rectangle::Contains(int x, int y) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | int | A vizsgálandó pont X koordinátája |
| y | int | A vizsgálandó pont Y koordinátája |

### Visszatérési érték

True, ha a megadott pont a jelenlegi objektum által képviselt téglalapon belül helyezkedik el, egyébként - false

## Rectangle::Contains(const Point\&) const metódus

Meghatározza, hogy a megadott pont a jelenlegi objektum által képviselt téglalapon belül helyezkedik-e el.

```cpp
bool System::Drawing::Rectangle::Contains(const Point &point) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | const [Point](../../point/)\& | A vizsgálandó pont |

### Visszatérési érték

True, ha a megadott pont a jelenlegi objektum által képviselt téglalapon belül helyezkedik el, egyébként - false

## Rectangle::Contains(const Rectangle\&) const metódus

Meghatározza, hogy a megadott téglalap a jelenlegi objektum által képviselt téglalapon belül helyezkedik-e el.

```cpp
bool System::Drawing::Rectangle::Contains(const Rectangle &rect) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | A vizsgálandó téglalap |

### Visszatérési érték

True, ha a megadott téglalap a jelenlegi objektum által képviselt téglalapon belül helyezkedik el, egyébként - false

## Lásd még

* Osztály [Rectangle](../)
* Osztály [Point](../../point/)
* Névterület [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)