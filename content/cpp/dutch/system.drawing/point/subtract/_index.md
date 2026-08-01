---
title: Subtract()
second_title: Aspose.Slides voor C++ API-referentie
description: Trekt de breedte- en hoogtewaarden van het opgegeven Size-object af van de X- en Y-coördinatenwaarden van het opgegeven Point-object respectievelijk.
type: docs
weight: 196
url: /nl/system.drawing/point/subtract/
---
## Point::Subtract(const Point\&, const Size\&) methode

Trekt de breedte- en hoogtewaarden van het opgegeven [Size](../../size/) object af van de X- en Y-coördinatenwaarden van het opgegeven [Point](../) object respectievelijk.

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | const [Point](../)\& | Het punt om te vertalen |
| size | const [Size](../../size/)\& | Het [Size](../../size/) object dat de waarden specificeert die moeten worden afgetrokken van de coördinatenwaarden van het **point** |

### Retourwaarde

Een nieuw [Point](../) object waarvan de X-coördinaatwaarde gelijk is aan het resultaat van de aftrekking van de breedtewaarde van **size** van de X-coördinaatwaarde van **point** en waarvan de Y-coördinaatwaarde gelijk is aan het resultaat van de aftrekking van de hoogtewaarde van **size** van de Y-coördinaatwaarde van **point**

## Zie ook

* Klasse [Point](../)
* Klasse [Size](../../size/)
* Namespace [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)