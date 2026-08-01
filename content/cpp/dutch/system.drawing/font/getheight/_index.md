---
title: GetHeight()
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft de regelafstand van het lettertype weer dat wordt weergegeven door het huidige object, in de huidige eenheid van een opgegeven Graphics-object.
type: docs
weight: 14
url: /nl/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) methode

Geeft de regelafstand van het lettertype weer dat wordt weergegeven door het huidige object, in de huidige eenheid van een opgegeven [Graphics](../../graphics/) object.

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Een [Graphics](../../graphics/) object dat de meeteenheden specificeert |

## Font::GetHeight(float) methode

Geeft de hoogte van het lettertype weer dat wordt weergegeven door het huidige object wanneer het wordt getekend op een weergaveapparaat met de opgegeven verticale resolutie.

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dpi | **float** | De verticale resolutie van het weergaveapparaat |

### Retourwaarde

De hoogte van het lettertype in pixels

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Graphics](../../graphics/)
* Klasse [Font](../)
* Naamruimte [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)