---
title: Point()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy új Point objektumot, és az X és Y koordinátaértékeket 0-ra inicializálja.
type: docs
weight: 1
url: /hu/system.drawing/point/point/
---
## Point::Point() konstruktor

Létrehoz egy új [Point](../) objektumot, és X és Y koordinátáinak értékét 0-ra állítja.

```cpp
System::Drawing::Point::Point()
```

## Point::Point(int, int) konstruktor

Létrehoz egy új [Point](../) objektumot, és a megadott értékekkel inicializálja.

```cpp
System::Drawing::Point::Point(int x, int y)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | int | Az X koordináta értéke |
| y | int | Az Y koordináta értéke |

## Point::Point(const Size\&) konstruktor

Létrehoz egy új [Point](../) objektumot, és X és Y koordinátáinak értékét a megadott [SizeF](../../sizef/) objektum szélességének és magasságának értékeivel állítja be megfelelően.

```cpp
System::Drawing::Point::Point(const Size &size)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| size | const [Size](../../size/)\& | Egy [SizeF](../../sizef/) objektum, amelynek szélesség és magasság értékeit használják az X és Y koordináták értékeinek inicializálásához a létrehozandó [Point](../) objektumban |

## Point::Point(int) konstruktor

Létrehoz egy új [Point](../) objektumot, és X koordináta értékét a megadott 32 bites egész magas 16 bitjével, Y koordináta értékét pedig a megadott 32 bites egész alacsony 16 bitjével állítja be.

```cpp
System::Drawing::Point::Point(int dw)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dw | int | A 32 bites egész érték, amelynek magas 16 bitje az X koordináta értékét, alacsony 16 bitje pedig a létrehozandó objektum Y koordináta értékét adja meg |

## Lásd még

* Osztály [Point](../)
* Osztály [Size](../../size/)
* Névterület [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)