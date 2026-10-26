---
title: BitVector32
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt einen einfachen leichten Bitvektor mit einfachem ganzzahligen oder booleschen Zugriff auf einen 32 Bit Speicher bereit.
type: docs
weight: 1
url: /de/system.collections.specialized/bitvector32/
---
## BitVector32 Klasse

Stellt einen einfachen leichten Bitvektor mit einfachem ganzzahligen oder [Boolean](../../system/boolean/) Zugriff auf einen 32-Bit-Speicher bereit.

```cpp
class BitVector32
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [BitVector32](./bitvector32/)() | Initialisiert eine neue leere Instanz von [BitVector32](./). |
|  [BitVector32](./bitvector32/)(**int32_t**) | Initialisiert eine neue Instanz der [BitVector32](./)-Struktur mit den angegebenen internen Daten. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | Initialisiert eine neue Instanz der [BitVector32](./)-Struktur mit den Informationen im angegebenen Wert. |
| static **int32_t** [CreateMask](./createmask/)() | Erstellt die erste Maske in einer Reihe. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | Erstellt die nächste Maske in einer Reihe. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | Erstellt den ersten Abschnitt in einer Reihe, mit dem angegebenen Maximalwert. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | Erstellt den nächsten Abschnitt in einer Reihe, mit dem angegebenen Maximalwert. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | Bestimmt, ob das angegebene Objekt dasselbe wie das aktuelle ist. |
| **int32_t** [get_Data](./get_data/)() | liefert die rohen Daten, die in diesem BitVector32 gespeichert sind... |
| **int32_t** [GetHashCode](./gethashcode/)() const | Gibt einen Hashcode für das aktuelle Objekt zurück. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | Ermittelt einen Wert, der angibt, ob alle angegebenen Bits gesetzt sind. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | Ermittelt den Wert für den angegebenen Abschnitt. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | Setzt einen Wert, der angibt, ob alle angegebenen Bits gesetzt sind. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | Setzt den Wert für den angegebenen Abschnitt. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | Konvertiert den durch den Werteparameter dargestellten Wert in eine Zeichenkette. |
| [String](../../system/string/) [ToString](./tostring/)() const | Konvertiert den durch das aktuelle Objekt dargestellten Wert in eine Zeichenkette. |

## Siehe auch

* Namensraum [System::Collections::Specialized](../)
* Bibliothek [Aspose.Slides](../../)