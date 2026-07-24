---
title: Index
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt einen Index in einer Sammlung dar. Der Index kann vom Anfang oder vom Ende aus angegeben werden. Dieser Typ sollte auf dem Stack zugewiesen und Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die Klasse System::SmartPtr, um Objekte dieses Typs zu verwalten."
type: docs
weight: 1015
url: /de/system/index/
---
## Index Klasse

Stellt einen Index in einer Sammlung dar. Der Index kann vom Anfang oder vom Ende aus angegeben werden. Dieser Typ sollte auf dem Stack zugewiesen und Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](../smartptr/), um Objekte dieses Typs zu verwalten.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [Equals](./equals/)(const [Index](./)\&) const | Bestimmt, ob die aktuelle Instanz und das angegebene [Index](./) dieselbe Position darstellen. |
| static constexpr [Index](./) [FromEnd](./fromend/)(**int32_t**) | Erstellt ein [Index](./), das relativ zum Ende der Sammlung ist. |
| static constexpr [Index](./) [get_End](./get_end/)() | Liefert ein [Index](./)-Objekt, das das Ende einer Sammlung darstellt. |
| constexpr **bool** [get_IsFromEnd](./get_isfromend/)() const | Liefert einen Wert, der angibt, ob der Index vom Ende aus ist. |
| static constexpr [Index](./) [get_Start](./get_start/)() | Liefert ein [Index](./)-Objekt, das den Anfang einer Sammlung darstellt. |
| constexpr **int32_t** [get_Value](./get_value/)() const | Liefert den Indexwert. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Gibt einen Hashcode für den aktuellen Index zurück. |
| **int32_t** [GetOffset](./getoffset/)(**int32_t**) const | Konvertiert das aktuelle [Index](./) in einen Versatz vom Anfang einer Sammlung mit der angegebenen Länge. |
| constexpr [Index](./index/)() | Erstellt eine Instanz, die den Anfang einer Sammlung darstellt. |
| constexpr [Index](./index/)(**int32_t**) | Erstellt eine Instanz, die die angegebene Position vom Anfang einer Sammlung darstellt. |
| constexpr [Index](./index/)(**int32_t**, **bool**) | Erstellt eine Instanz, die den angegebenen Index darstellt. |

## Siehe Auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)