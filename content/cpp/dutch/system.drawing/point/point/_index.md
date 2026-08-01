---
title: Point()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw Point object en initialiseert de X- en Y-coördinaatwaarden met 0.
type: docs
weight: 1
url: /nl/system.drawing/point/point/
---
## Point::Point() constructor

Construeert een nieuw [Point](../) object en initialiseert de X- en Y-coördinaatwaarden met 0.

```cpp
System::Drawing::Point::Point()
```

## Point::Point(int, int) constructor

Construeert een nieuw [Point](../) object en initialiseert het met de opgegeven waarden.

```cpp
System::Drawing::Point::Point(int x, int y)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De waarde van de X-coördinaat |
| y | int | De waarde van de Y-coördinaat |

## Point::Point(const Size\&) constructor

Construeert een nieuw [Point](../) object en initialiseert de X- en Y-coördinaatwaarden met de breedte- en hoogtewaarden van het gespecificeerde [SizeF](../../sizef/) object respectievelijk.

```cpp
System::Drawing::Point::Point(const Size &size)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| size | const [Size](../../size/)\& | Een [SizeF](../../sizef/) object waarvan de breedte- en hoogtewaarden worden gebruikt om de X- en Y-coördinaatwaarden van het [Point](../) object dat wordt aangemaakt te initialiseren |

## Point::Point(int) constructor

Construeert een nieuw [Point](../) object en initialiseert de X-coördinaatwaarde met een waarde die gevormd wordt door de hoge 16 bits van het opgegeven 32-bit geheel getal, en de Y-coördinaatwaarde met een waarde gevormd door de lage 16 bits van het opgegeven 32-bit geheel getal.

```cpp
System::Drawing::Point::Point(int dw)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dw | int | De 32-bit geheel-getalwaarde waarvan de hoge 16 bits de X-coördinaatwaarde bepalen en de lage 16 bits de Y-coördinaatwaarde van het te maken object bepalen |

## Zie ook

* Klasse [Point](../)
* Klasse [Size](../../size/)
* Namespace [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)