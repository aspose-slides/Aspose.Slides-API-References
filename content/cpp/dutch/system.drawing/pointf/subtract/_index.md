---
title: Subtract()
second_title: Aspose.Slides voor C++ API-referentie
description: Trekt de breedte- en hoogte-waarden van het opgegeven SizeF-object af van de X- en Y-coördinaatwaarden van het opgegeven PointF-object respectievelijk.
type: docs
weight: 157
url: /nl/system.drawing/pointf/subtract/
---
## PointF::Subtract(const PointF\&, const SizeF\&) methode


Vermindert de breedte- en hoogte-waarden van het opgegeven [SizeF](../../sizef/) object van de X- en Y-coördinaatwaarden van het opgegeven [PointF](../) object respectievelijk.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const SizeF &size)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [PointF](../)\& | Het **point** om te vertalen |
| size | const [SizeF](../../sizef/)\& | Het [SizeF](../../sizef/) object dat de waarden specificeert die moeten worden afgetrokken van de coördinaatwaarden van het **point** |

### Retourwaarde

Een nieuw [PointF](../) object waarvan de X-coördinaatwaarde gelijk is aan het resultaat van de aftrekking van de breedtewaarde van **size** van de X-coördinaatwaarde van **point** en waarvan de Y-coördinaatwaarde gelijk is aan het resultaat van de aftrekking van de hoogtewaarde van **size** van de Y-coördinaatwaarde van **point**.

## PointF::Subtract(const PointF\&, const Size\&) methode


Vermindert de breedte- en hoogte-waarden van het opgegeven [Size](../../size/) object van de X- en Y-coördinaatwaarden van het opgegeven [PointF](../) object respectievelijk.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const Size &size)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [PointF](../)\& | Het **point** om te vertalen |
| size | const [Size](../../size/)\& | Het [Size](../../size/) object dat de waarden specificeert die moeten worden afgetrokken van de coördinaatwaarden van het **point** |

### Retourwaarde

Een nieuw [PointF](../) object waarvan de X-coördinaatwaarde gelijk is aan het resultaat van de aftrekking van de breedtewaarde van **size** van de X-coördinaatwaarde van **point** en waarvan de Y-coördinaatwaarde gelijk is aan het resultaat van de aftrekking van de hoogtewaarde van **size** van de Y-coördinaatwaarde van **point**.

## Zie ook

* Klasse [PointF](../)
* Klasse [SizeF](../../sizef/)
* Klasse [Size](../../size/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)