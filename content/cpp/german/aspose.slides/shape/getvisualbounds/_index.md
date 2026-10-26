---
title: GetVisualBounds()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die visuellen Grenzen der Form, die aus ihrem gerenderten Inhalt berechnet werden.
type: docs
weight: 677
url: /de/aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() Methode

Ermittelt die visuellen Grenzen der Form, die aus ihrem gerenderten Inhalt berechnet werden.

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```

### Rückgabewert

Ein [System::Drawing::RectangleF](../../../system.drawing/rectanglef/), der die visuellen Grenzen der Form in Folienkoordinaten darstellt.

## Anmerkungen

Das zurückgegebene Rechteck stellt die achsen ausgerichteten Grenzen aller von der Form während des Renderns erzeugten Inhalte im Folienkoordinatenraum dar.

Diese Grenzen können von den Modellgrenzen der Form ([Shape::X](../), [Shape::Y](../), [Shape::Width](../), [Shape::Height](../)) abweichen und können negative Koordinaten enthalten, wenn der gerenderte Inhalt über den Folienursprung hinausgeht.

Die visuellen Grenzen berücksichtigen renderbezogene Aspekte wie Transformationen (zum Beispiel Rotation), Strichbreite und Verbindungen, Textlayout und Überlauf, [SmartArt](../../../aspose.slides.smartart/) Geometrie sowie weitere Layout-Effekte, die das endgültige gerenderte Erscheinungsbild der Form beeinflussen.

Die zurückgegebenen Grenzen werden nicht auf das Folienrechteck zugeschnitten.

## Siehe Auch

* Klasse [RectangleF](../../../system.drawing/rectanglef/)
* Klasse [Shape](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)