---
title: Inflate()
second_title: Aspose.Slides für C++ API-Referenz
description: Erhöht die Breite und Höhe des durch das aktuelle Objekt dargestellten Rechtecks, wobei der geometrische Mittelpunkt des Rechtecks beibehalten wird. Breite und Höhe werden in beide Richtungen um die angegebenen Beträge vergrößert.
type: docs
weight: 261
url: /de/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(int, int) Methode

Erhöht die Breite und Höhe des durch das aktuelle Objekt repräsentierten Rechtecks, wobei der geometrische Mittelpunkt des Rechtecks beibehalten wird. Breite und Höhe werden in beide Richtungen um die angegebenen Beträge vergrößert.

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | int | Die Menge, um die die Breite des Rechtecks in beide Richtungen vergrößert wird |
| height | int | Die Menge, um die die Höhe des Rechtecks in beide Richtungen vergrößert wird |

## Rectangle::Inflate(const Size\&) Methode

Erhöht die Breite und Höhe des durch das aktuelle Objekt repräsentierten Rechtecks, wobei der geometrische Mittelpunkt des Rechtecks beibehalten wird. Breite und Höhe werden in beide Richtungen um die durch die Breiten- und Höhenwerte des angegebenen Size-Objekts festgelegten Beträge entsprechend vergrößert.

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | const [Size](../../size/)\& | Das [Size](../../size/)-Objekt, das die Beträge angibt, um die die Breite und Höhe des Rechtecks vergrößert werden sollen |

## Rectangle::Inflate(const Rectangle\&, int, int) Methode

Erhöht die Breite und Höhe des durch das angegebene Objekt repräsentierten Rechtecks, wobei der geometrische Mittelpunkt des Rechtecks beibehalten wird. Breite und Höhe werden in beide Richtungen um die angegebenen Beträge vergrößert.

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | Ein Rechteck, das aufgeblasen werden soll |
| x | int | Die Menge, um die die Breite des Rechtecks in beide Richtungen vergrößert wird |
| y | int | Die Menge, um die die Höhe des Rechtecks in beide Richtungen vergrößert wird |

### Rückgabewert

Das [Rectangle](../)-Objekt, das das vergrößerte Rechteck darstellt

## Siehe auch

* Klasse [Rectangle](../)
* Klasse [Size](../../size/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)