---
title: Inflate()
second_title: Aspose.Slides für C++ API-Referenz
description: Erhöht die Breite und Höhe des durch das aktuelle Objekt dargestellten Rechtecks, wobei die Lage des geometrischen Zentrums des Rechtecks beibehalten wird. Breite und Höhe werden in beide Richtungen um die angegebenen Werte vergrößert.
type: docs
weight: 261
url: /de/system.drawing/rectanglef/inflate/
---
## RectangleF::Inflate(float, float) Methode


Erhöht die Breite und Höhe des durch das aktuelle Objekt dargestellten Rechtecks, wobei die Lage des geometrischen Zentrums des Rechtecks beibehalten wird. Breite und Höhe werden in beide Richtungen um die angegebenen Werte vergrößert.

```cpp
void System::Drawing::RectangleF::Inflate(float width, float height)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | **float** | Der Betrag, um den die Breite des Rechtecks in beide Richtungen vergrößert werden soll |
| height | **float** | Der Betrag, um den die Höhe des Rechtecks in beide Richtungen vergrößert werden soll |

## RectangleF::Inflate(const SizeF\&) Methode


Erhöht die Breite und Höhe des durch das aktuelle Objekt dargestellten Rechtecks, wobei die Lage des geometrischen Zentrums des Rechtecks beibehalten wird. Die Breite und Höhe werden in beide Richtungen um die Werte erhöht, die durch die Breiten- und Höhenwerte des angegebenen Größenobjekts entsprechend angegeben sind.

```cpp
void System::Drawing::RectangleF::Inflate(const SizeF &size)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | const [SizeF](../../sizef/)\& | Das [SizeF](../../sizef/)-Objekt, das die Werte zum Erhöhen der Breite und Höhe des Rechtecks angibt |

## RectangleF::Inflate(const RectangleF\&, float, float) Methode


Erhöht die Breite und Höhe des durch das angegebene Objekt dargestellten Rechtecks, wobei die Lage des geometrischen Zentrums des Rechtecks beibehalten wird. Breite und Höhe werden in beide Richtungen um die angegebenen Werte vergrößert.

```cpp
static RectangleF System::Drawing::RectangleF::Inflate(const RectangleF &rect, float x, float y)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | Ein Rechteck, das vergrößert werden soll |
| x | **float** | Der Betrag, um den die Breite des Rechtecks in beide Richtungen vergrößert werden soll |
| y | **float** | Der Betrag, um den die Höhe des Rechtecks in beide Richtungen vergrößert werden soll |

### Rückgabewert

Das [RectangleF](../)-Objekt, das das vergrößerte Rechteck darstellt

## Siehe auch

* Klasse [RectangleF](../)
* Klasse [SizeF](../../sizef/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)