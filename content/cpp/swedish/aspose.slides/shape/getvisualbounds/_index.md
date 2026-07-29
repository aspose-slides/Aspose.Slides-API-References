---
title: GetVisualBounds()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll.
type: docs
weight: 677
url: /sv/aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() metod


Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll.

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```


### Returvärde

En [System::Drawing::RectangleF](../../../system.drawing/rectanglef/) som representerar de visuella gränserna för formen i bildkoordinater.
## Anmärkningar


Den returnerade rektangeln representerar de axeljusterade gränserna för allt innehåll som genereras av formen under renderingen i bildkoordinatrymden.

Dessa gränser kan skilja sig från formens modellgränser ([Shape::X](../), [Shape::Y](../), [Shape::Width](../), [Shape::Height](../)) och kan innehålla negativa koordinater om det renderade innehållet sträcker sig bortom bildens ursprung.

De visuella gränserna tar hänsyn till renderingsrelaterade aspekter såsom transformationer (till exempel rotation), linjebredd och fogar, textlayout och översvämning, [SmartArt](../../../aspose.slides.smartart/) geometri, samt andra layout-effekter som påverkar den slutgiltiga renderade utseendet på formen.

De returnerade gränserna klipps inte till bildrektangeln. 

## Se även

* Klass [RectangleF](../../../system.drawing/rectanglef/)
* Klass [Shape](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)