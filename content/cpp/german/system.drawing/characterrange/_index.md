---
title: CharacterRange
second_title: Aspose.Slides für C++ API Referenz
description: "Stellt einen Bereich von Zeichenpositionen in einer Zeichenkette dar. Dieser Typ sollte auf dem Stack alloziert und per Wert oder Referenz an Funktionen übergeben werden. Verwenden Sie niemals die System::SmartPtr Klasse, um Objekte dieses Typs zu verwalten."
type: docs
weight: 40
url: /de/system.drawing/characterrange/
---
## CharacterRange Klasse


Stellt einen Bereich von Zeichenpositionen in einer Zeichenkette dar. Dieser Typ sollte auf dem Stack allokiert und per Wert oder Referenz an Funktionen übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../../system/smartptr/) Klasse, um Objekte dieses Typs zu verwalten.

```cpp
class CharacterRange
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [CharacterRange](./characterrange/)(**int32_t**, **int32_t**) | Konstruiert eine neue Instanz der [CharacterRange](./) Klasse, die den angegebenen Bereich darstellt. |
|  [CharacterRange](./characterrange/)() | Konstruiert eine neue Instanz der [CharacterRange](./) Klasse, die einen leeren Bereich darstellt. |
| **int32_t** [get_First](./get_first/)() const | Gibt die Position des ersten Zeichens des von dem aktuellen Objekt dargestellten Bereichs zurück. |
| **int32_t** [get_Length](./get_length/)() const | Gibt die Anzahl der Zeichen im von dem aktuellen Objekt dargestellten Bereich zurück. |
| **bool** [operator!=](./operator_not_equal/)(const [CharacterRange](./)\&) const | Bestimmt, ob das aktuelle und das angegebene Objekt unterschiedliche Bereiche darstellen. |
| **bool** [operator==](./operator_equal_equal/)(const [CharacterRange](./)\&) const | Bestimmt, ob das aktuelle und das angegebene Objekt denselben Bereich darstellen. |
| void [set_First](./set_first/)(**int32_t**) | Setzt die Position des ersten Zeichens des von dem aktuellen Objekt dargestellten Bereichs. |
| void [set_Length](./set_length/)(**int32_t**) | Gibt die Anzahl der Zeichen im von dem aktuellen Objekt dargestellten Bereich zurück. |
## Siehe auch

* Namensraum [System::Drawing](../)
* Bibliothek [Aspose.Slides](../../)