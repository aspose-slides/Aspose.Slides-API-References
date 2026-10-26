---
title: GetVisualBounds()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de visuele grenzen van de vorm op, berekend op basis van de gerenderde inhoud.
type: docs
weight: 677
url: /nl/aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() methode

Haalt de visuele grenzen van de vorm op, berekend op basis van de gerenderde inhoud.

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```

### Retourwaarde

Een [System::Drawing::RectangleF](../../../system.drawing/rectanglef/) die de visuele grenzen van de vorm in dia-coördinaten vertegenwoordigt.

## Opmerkingen

De geretourneerde rechthoek vertegenwoordigt de as-uitgelijnde grenzen van alle inhoud die door de vorm tijdens het renderen wordt geproduceerd in de dia-coördinatenruimte.

Deze grenzen kunnen afwijken van de modelgrenzen van de vorm ([Shape::X](../), [Shape::Y](../), [Shape::Width](../), [Shape::Height](../)) en kunnen negatieve coördinaten bevatten als de gerenderde inhoud verder reikt dan de oorsprong van de dia.

De visuele grenzen houden rekening met rendergerelateerde aspecten zoals transformaties (bijvoorbeeld rotatie), lijnbreedte en verbindingen, tekstindeling en overflow, [SmartArt](../../../aspose.slides.smartart/) geometrie, en andere layouteffecten die de uiteindelijke gerenderde weergave van de vorm beïnvloeden.

De geretourneerde grenzen worden niet bijgesneden tot de dia-rechthoek. 

## Zie ook

* Klasse [RectangleF](../../../system.drawing/rectanglef/)
* Klasse [Shape](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)