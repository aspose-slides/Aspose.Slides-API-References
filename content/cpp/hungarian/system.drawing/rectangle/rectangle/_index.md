---
title: Rectangle()
second_title: Aspose.Slides for C++ API-referencia
description: Új Rectangle objektum példányt hoz létre, amely egy olyan téglalapot képvisel, amelynek X és Y koordinátái, valamint a width és height értékei 0-ra vannak állítva.
type: docs
weight: 1
url: /hu/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() konstruktor


Új [Rectangle](../) objektum példányt hoz létre, amely egy olyan téglalapot képvisel, amelynek X és Y koordinátái, valamint a szélesség és magasság értéke 0.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) konstruktor


Új [Rectangle](../) objektum példányt hoz létre, amely egy olyan téglalapot képvisel, amelynek bal felső sarkának meghatározott koordinátái, valamint a szélesség és magasság értékei vannak megadva.

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | int | A téglalap bal felső sarkának X koordinátája |
| y | int | A téglalap bal felső sarkának Y koordinátája |
| width | int | A téglalap szélessége |
| height | int | A téglalap magassága |

## Rectangle::Rectangle(const Point\&, const Size\&) konstruktor


Új [Rectangle](../) objektum példányt hoz létre, amely egy olyan téglalapot képvisel, amelynek bal felső sarkának koordinátái egy [Point](../../point/) osztálypéldányként, szélessége és magassága pedig egy [Size](../../size/) osztálypéldányként vannak megadva.

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| location | const [Point](../../point/)\& | Meghatározza a téglalap bal felső sarkának helyét |
| size | const [Size](../../size/)\& | Meghatározza a téglalap szélességét és magasságát |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_\&) konstruktor


Új [Rectangle](../) objektum példányt hoz létre, amely a megadott téglalapnak megfelelő téglalapot képviseli.

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | Egy **System::Windows::Forms::Screen::Rectangle_** osztálypéldány, amely meghatározza a létrehozandó objektum által képviselt téglalap pozícióját és méretét |

## Lásd még

* Osztály [Rectangle](../)
* Osztály [Point](../../point/)
* Osztály [Size](../../size/)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)