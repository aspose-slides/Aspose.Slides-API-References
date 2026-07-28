---
title: GetVisualBounds()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera granice wizualne kształtu obliczone na podstawie jego renderowanej zawartości.
type: docs
weight: 677
url: /pl/aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() metoda

Pobiera granice wizualne kształtu obliczone na podstawie jego renderowanej zawartości.

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```

### Wartość zwracana

Obiekt [System::Drawing::RectangleF](../../../system.drawing/rectanglef/) reprezentujący granice wizualne kształtu w układzie współrzędnych slajdu.

## Uwagi

Zwrócony prostokąt reprezentuje granice osiowo wyrównane całej zawartości generowanej przez kształt podczas renderowania w przestrzeni współrzędnych slajdu.

Te granice mogą różnić się od granic modelu kształtu ([Shape::X](../), [Shape::Y](../), [Shape::Width](../), [Shape::Height](../)) i mogą zawierać ujemne współrzędne, jeśli renderowana zawartość wykracza poza początek slajdu.

Granice wizualne uwzględniają aspekty związane z renderowaniem, takie jak przekształcenia (na przykład obrót), szerokość i połączenia obrysów, układ tekstu i jego przepełnienie, [SmartArt](../../../aspose.slides.smartart/) geometrię oraz inne efekty układu wpływające na ostateczny wygląd renderowanego kształtu.

Zwrócone granice nie są przycinane do prostokąta slajdu.

## Zobacz także

* Klasa [RectangleF](../../../system.drawing/rectanglef/)
* Klasa [Shape](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)