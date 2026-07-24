---
title: Range
second_title: "Aspose.Slides für C++ API-Referenz"
description: "Stellt einen Bereich mit einem Start- und End-Index dar. Dieser Typ sollte auf dem Stack zugewiesen und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die System::SmartPtr Klasse, um Objekte dieses Typs zu verwalten."
type: docs
weight: 1197
url: /de/system/range/
---
## Range Klasse

Stellt einen Bereich mit einem Start- und End-Index dar. Dieser Typ sollte auf dem Stack zugewiesen und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../smartptr/) Klasse, um Objekte dieses Typs zu verwalten.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | Erstellt einen Bereich, der am Anfang der Sammlung beginnt und am angegebenen End-Index endet. |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | Bestimmt, ob der aktuelle Bereich dem angegebenen Bereich entspricht. |
| static constexpr [Range](./) [get_All](./get_all/)() | Gibt ein [Range](./) zurück, das die gesamte Sammlung darstellt. |
| const [Index](../index/)\& [get_End](./get_end/)() const | Liefert den End-Index. |
| const [Index](../index/)\& [get_Start](./get_start/)() const | Liefert den Start-Index. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Gibt einen Hash-Code für den aktuellen Bereich zurück. |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | Berechnet den nullbasierten Startoffset und die Länge für die angegebene Sammlungslänge. |
| constexpr [Range](./range/)() | Konstruiert einen leeren Bereich. |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | Konstruiert ein [Range](./) aus den angegebenen Start- und End-Indizes. |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | Erstellt einen Bereich, der am angegebenen Start-Index beginnt und bis zum Ende der Sammlung reicht. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)