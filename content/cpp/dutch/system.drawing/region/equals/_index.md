---
title: Equals()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of de opgegeven regio identiek is aan de regio die wordt vertegenwoordigd door het huidige object op het opgegeven tekenoppervlak.
type: docs
weight: 157
url: /nl/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) methode


Bepaalt of de opgegeven regio identiek is aan de regio die wordt vertegenwoordigd door het huidige object op het opgegeven tekenoppervlak.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | De regio om deze regio mee te vergelijken |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Een tekenoppervlak |

### Retourwaarde

True als het binnenste van de opgegeven regio identiek is aan het binnenste van de regio die wordt vertegenwoordigd door het huidige objcet wanneer de transformatie die gekoppeld is aan de **g**-parameter wordt toegepast; anders - false

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Region](../)
* Klasse [Graphics](../../graphics/)
* Namespace [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)