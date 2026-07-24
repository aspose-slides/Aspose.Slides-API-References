---
title: CompareTo()
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht zwei Datum- und Uhrzeitwerte, die vom aktuellen Objekt und der angegebenen Instanz der DateTime-Klasse repräsentiert werden, und gibt den Wert zurück, der die relativen Positionen der Werte auf der Zeitleiste angibt.
type: docs
weight: 443
url: /de/system/datetime/compareto/
---
## DateTime::CompareTo(DateTime) const Methode

Vergleicht zwei Datums- und Uhrzeitwerte, die vom aktuellen Objekt und der angegebenen Instanz der [DateTime](../)-Klasse repräsentiert werden, und gibt den Wert zurück, der die relativen Positionen der Werte auf der Zeitleiste angibt.

```cpp
constexpr int System::DateTime::CompareTo(DateTime value) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DateTime](../) | Eine Instanz der [DateTime](../)-Klasse zum Vergleich mit dem aktuellen Objekt |

### Rückgabewert

Ein Wert, der kleiner als 0 ist, wenn das aktuelle Objekt einen früheren Wert darstellt als der von **value** repräsentierte; 0, wenn die von beiden Objekten dargestellten Werte identisch sind; ein Wert, der größer als 0 ist, wenn der vom aktuellen Objekt dargestellte Wert später liegt als der von **value** dargestellte.

## Siehe auch

* Klasse [DateTime](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)