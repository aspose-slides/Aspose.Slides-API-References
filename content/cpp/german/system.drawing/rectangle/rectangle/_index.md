---
title: Rectangle()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Instanz des Rectangle-Objekts, das ein Rechteck mit den X- und Y-Koordinaten sowie Breite- und Höhenwerten von 0 darstellt.
type: docs
weight: 1
url: /de/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() Konstruktor


Erzeugt eine neue Instanz des [Rectangle](../)-Objekts, das ein Rechteck mit den X- und Y-Koordinaten sowie Breite- und Höhenwerten von 0 darstellt.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) Konstruktor


Erzeugt eine neue Instanz des [Rectangle](../)-Objekts, das ein Rechteck mit den angegebenen Koordinaten seiner oberen linken Ecke sowie Breite und Höhe darstellt.

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Ein Wert der X-Koordinate der oberen linken Ecke des Rechtecks |
| y | int | Ein Wert der Y-Koordinate der oberen linken Ecke des Rechtecks |
| width | int | Die Breite des Rechtecks |
| height | int | Die Höhe des Rechtecks |

## Rectangle::Rectangle(const Point\&, const Size\&) Konstruktor


Erzeugt eine neue Instanz des [Rectangle](../)-Objekts, das ein Rechteck mit den Koordinaten seiner oberen linken Ecke, angegeben durch eine Instanz der [Point](../../point/)-Klasse, und seiner Breite und Höhe, angegeben durch eine Instanz der [Size](../../size/)-Klasse, darstellt.

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| location | const [Point](../../point/)\& | Gibt die Position der oberen linken Ecke des Rechtecks an |
| size | const [Size](../../size/)\& | Gibt die Breite und Höhe des Rechtecks an |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_\&) Konstruktor


Erzeugt eine neue Instanz des [Rectangle](../)-Objekts, das das dem angegebenen Rechteck entsprechende Rechteck darstellt.

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | Eine Instanz der **System::Windows::Forms::Screen::Rectangle_**-Klasse, die die Position und Größe des Rechtecks angibt, das vom zu erstellenden Objekt dargestellt wird |

## Siehe auch

* Klasse [Rectangle](../)
* Klasse [Point](../../point/)
* Klasse [Size](../../size/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)